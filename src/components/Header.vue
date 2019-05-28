<template>
  <div class="header">
    <div class="container">
      <div class="f-s-b">
        <div class="logo">Logo</div>
        <div class="abz">abz.agency</div>
        <nav class="f-c">
          <router-link class="header__link link1" to="/">About me</router-link>
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
        <div class="user_img">Img</div>
        <div class="login_logo">Login</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style></style>
