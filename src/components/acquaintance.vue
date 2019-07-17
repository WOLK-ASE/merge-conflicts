<template>
  <div class="acquaintance">
    <div class="container">
      <div class="acquaintance-title h2">Let's get acquainted</div>
      <div class="flex">
        <div class="acquaintance-img"></div>
        <div class="acquaintance-data">
          <h3 class="acquaintance-data__title">
            I am cool frontend developer
          </h3>
          <p class="acquaintance-data__text m">
            When real users have a slow experience on mobile, they're much less
            likely to find what they are looking for or purchase from you in the
            future. For many sites this equates to a huge missed opportunity,
            especially when more than half of visits are abandoned if a mobile
            page takes over 3 second to load. <br /><br />
            Last week, Google search and Ads teams announced two new speed
            initiatives to help improve user-experience on web.
          </p>
          <button class="btn-text">Sign Up</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "acquaintance"
};
</script>

<style>
.acquaintance-title {
  padding-top: 139px;
  padding-bottom: 25px;
  margin-left: 270px;
}
.acquaintance-img {
  background-image: url("../assets/imgs/man-mobile.svg");
  width: 289px;
  height: 285px;
}
.acquaintance-data {
  padding-left: 30px;
  padding-top: 15px;
}
.acquaintance-data__text {
  width: 613px;
  height: 148px;
}
.acquaintance-data button {
  margin-top: -20px;
}
</style>
