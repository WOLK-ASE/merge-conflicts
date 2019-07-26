<template>
  <div class="registration">
    <div class="container">
      <div class="reg-title">
        <div class="h2">Register to get a work</div>
        <p class="l">
          Attention! After successful registration and alert, update the list of
          users in the block from the top
        </p>
      </div>

      <!--          <form action="Потом думаю пригодится">-->
      <div class="flex input-section">
        <div class="form-group">
          <div class="label">Name</div>
          <input type="text" class="input" placeholder="Your name" />
        </div>
        <div class="form-group">
          <div class="label">Email</div>
          <input type="text" class="input" placeholder="Your email" />
        </div>
        <div class="form-group">
          <div class="label">Phone</div>
          <input type="text" class="input" placeholder="+38 (___)  ___ __ __" />
        </div>
      </div>
      <div class="form-select">
        <img src="../assets/icons/caret-down.svg" class="caret-down" />
        <select class="position">
          <option>Select your position</option>
          <option value="1">Designer</option>
          <option value="2">Frontend developer</option>
          <option value="3">Backend developer</option>
        </select>
      </div>
      <!--          </form>-->
      <el-select v-model="value" placeholder="Select your position">
        <el-option
                v-for="item in options"
                :key="item.value"
                :label="item.label"
                :value="item.value">
        </el-option>
      </el-select>
    </div>
  </div>
</template>

<script>
  import Vue from "vue";
  import { Select, Option } from "element-ui";
  [Select, Option].forEach(i => Vue.component(i.name, i));

export default {
  name: "registration",
  data(){
    return {
      options: [{
        value: 'Option1',
        label: 'Designer'
      }, {
        value: 'Option2',
        label: 'Frontend developer'
      }, {
        value: 'Option3',
        label: 'Backend developer'
      }],
      value: ''
    }
  }
};

</script>

<style>
  .el-select .el-input {
    font-size: 23px;
    padding: 15px 290px 17px 11px;
    border-radius: 5px;
    border: none;
  }
  .el-select .el-input .el-select__caret {
    background-image: url("../assets/icons/caret-down.svg");
    size: 100%;
    background-repeat: no-repeat;

  }

.reg-title {
  text-align: center;
  line-height: 29px;
  padding: 10px 120px 50px 0px;
}
.input-section {
  margin: 10px;

}
.registration .position {
  font-size: 16px;
  padding: 15px 290px 17px 11px;
  border-radius: 5px;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}
.caret-down {
  position: relative;
  left: 440px;
}
</style>
