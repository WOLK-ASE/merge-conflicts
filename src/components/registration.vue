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
      <div class="f-s-b input-section">
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
    </div>
  </div>
</template>

<script>
export default {
  name: "registration"
};
</script>

<style>
/*.el-select .el-input {*/
/*  font-size: 23px;*/
/*  padding: 15px 290px 17px 11px;*/
/*  border-radius: 5px;*/
/*  border: none;*/
/*}*/
/*.el-select .el-input .el-select__caret {*/
/*  background-image: url("../assets/icons/caret-down.svg");*/
/*  size: 100%;*/
/*  background-repeat: no-repeat;*/

/*}*/

.reg-title {
  text-align: center;
  line-height: 29px;
  padding: 5px 0px 45px 0px;
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
.form-group:nth-child(odd) {
  margin-left: 30px;
  margin-right: 30px;
}
</style>
