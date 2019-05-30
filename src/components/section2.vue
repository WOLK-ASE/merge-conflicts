<template>
  <div class="section2">
    <div class="container">
      <div class="section2-title h2">Let's get acquainted</div>
      <div class="f-j-c">
        <div class="section2-img"></div>
        <div class="section2-data">
          <div class="section2-data__title h3">
            I am cool frontend developer
          </div>
          <div class="section2-data__text">
            When real users have a slow experience on mobile, they're much less
            likely to find what they are looking for or purchase from you in the
            future. For many sites this equates to a huge missed opportunity,
            especially when more than half of visits are abandoned if a mobile
            page takes over 3 second to load. <br /><br />
            Last week, Google search and Ads teams announced two new speed
            initiatives to help improve user-experience on web.
          </div>
          <button class="btn-text">Sign Up</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "section2"
};
</script>

<style>
.section2-title {
  text-align: center;
  padding-top: 139px;
  padding-bottom: 25px;
}
.section2-img {
  background-image: url("../assets/imgs/man-mobile.svg");
  width: 289px;
  height: 285px;
}
.section2-data {
  padding-left: 30px;
  padding-top: 15px;
}
.section2-data__text {
  width: 613px;
  height: 148px;
}
</style>
