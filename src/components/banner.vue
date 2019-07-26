<template xmlns="http://www.w3.org/1999/html">
  <div class="banner">
    <div class="container">
      <div class="banner-content">
        <h1 class="banner-content__title">
          Test assignment for Frontend Developer position
        </h1>
        <p class="banner-content__text">
          We kindly remind your that your test assignment should be submitted as
          a link to github/bitbucket repository. Please be patient, we consider
          and respond to every application that meets minimum requirements. We
          look forward  to your submission. Good luck!
        </p>
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
  padding-top: 60px;
}
.banner-content {
  padding: 100px 0 158px 30px;
}
.banner-content__title {
  height: 166px;
  color: #ffffff;
  width: 500px;
}
.banner-content__text {
  height: 146px;
  color: #ffffff;
  font-size: 20px;
  line-height: 26px;
  margin: 31px 0 50px 0;
  width: 430px;
}
</style>
