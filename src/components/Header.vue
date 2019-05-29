<template>
  <div class="header">
    <div class="container">
      <div class="f-s-b">
        <div class="logo"></div>
        <nav class="f-c">
          <router-link class="header__link link1" to="/about">About me</router-link>
          <router-link class="header__link link1" to="/"
            >Relationships</router-link
          >
          <router-link class="header__link link1" to="/"
            >Requirements</router-link
          >
          <router-link class="header__link link1" to="/">Users</router-link>
          <router-link class="header__link link1" to="/">Sign Up</router-link>
        </nav>
        <div class="user_name">
          Superstar <br />
          Superstar@gmail.com
        </div>
        <div class="user_img"></div>
        <div class="sign-out"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style>
.logo {
  background-image: url("../assets/logo/logo.svg");
  width: 134px;
  height: 24px;
  margin-bottom: 20px;
  margin-top: 20px;
}
  .header__link {
  margin-left: 30px;
  margin-right: 30px;
  margin-top: 24px;
  margin-bottom: 24px;
}
.user_name {
  text-align: end;

}
.user_img {
background-image: url("../assets/imgs/user-superstar-2x.jpg");
  background-size: cover;
  width: 40px;
  height: 40px;
  border-radius: 50%;
}
.sign-out {
  background-image: url("../assets/icons/sign-out.svg");
  width: 24px;
  height: 20px;
  margin-top: 22px;

}
</style>
