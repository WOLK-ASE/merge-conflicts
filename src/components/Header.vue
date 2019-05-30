<template>
  <div class="header">
    <div class="container">
      <div class="flex">
        <div class="logo"></div>
        <nav class="flex">
          <router-link class="header__link link1" to="/about"
            >About me</router-link
          >
          <router-link class="header__link link1" to="/"
            >Relationships</router-link
          >
          <router-link class="header__link link1" to="/"
            >Requirements</router-link
          >
          <router-link class="header__link link1" to="/">Users</router-link>
          <router-link class="header__link link1" to="/">Sign Up</router-link>
        </nav>
        <div class="user-data">
          <div class="user-data__name">Superstar</div>
          <div class="user-data__mail">Superstar@gmail.com</div>
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
.header {
  background-color: white;
  position: fixed;
  z-index: 2;
  width: 100%;
  margin-right: auto;
  margin-left: auto;
}
.logo {
  background-image: url("../assets/logo/logo.svg");
  background-repeat: no-repeat;
  width: 134px;
  height: 24px;
  margin: 20px 52px 20px 31px;
}
.header__link {
  margin: 24px 15px 24px 15px;
}
.user-data__name {
  text-align: end;
  margin-top: 18px;
  font-size: 14px;
}
.user-data__mail {
  margin-left: 55px;
  margin-bottom: 17px;
  font-size: 12px;
}
.user_img {
  background-image: url("../assets/imgs/user-superstar-2x.jpg");
  background-size: cover;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin: 14px;
}
.sign-out {
  background-image: url("../assets/icons/sign-out.svg");
  width: 24px;
  height: 20px;
  margin-top: 22px;
  margin-right: 32px;
}
</style>
