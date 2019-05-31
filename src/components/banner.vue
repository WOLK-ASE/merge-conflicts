<template>
  <div class="banner">
    <div class="container">
      <div class="banner-content">
        <div class="banner-content__title h1">
          Test assignment for Frontend Developer position
        </div>
        <div class="banner-content__text">
          We kindly remind your that your test assignment should be submitted as
          a link to github/bitbucket repository. Please be patient, we consider
          and respond to every application that meets minimum requirements. We
          look forward to your submission. Good luck!
        </div>
        <button class="banner-content__btn btn1">Sign Up</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "banner"
};
</script>

<style>
.banner {
  background-image: url("../assets/imgs/bg-1.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  width: auto;
  margin-right: auto;
  margin-left: auto;
  padding-top: 60px;
}
.banner-content {
  padding: 139px 0 158px 31px;
}
.banner-content__title {
  width: 450px;
  height: 166px;
  color: #ffffff;
}
.banner-content__text {
  width: 430px;
  height: 150px;
  color: #ffffff;
  font-size: 20px;
  line-height: 26px;
  margin: 31px 0 45px 0;
}
</style>
