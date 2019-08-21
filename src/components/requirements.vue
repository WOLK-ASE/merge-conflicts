<template>
  <div class="requirements">
    <div class="container">
      <h2 class="requirements-title">
        General requirements for the test task
      </h2>
      <div class="flex requirements-data">
        <p class="m requirements-data__text">
          Users want to find answers to their questions quickly and data<br />
          shows that people really care about how quickly their pages load.<br />
          The Search team announced speed would be a ranking signal for<br />
          desktop searches in 2010 and as of this month(July 2018), page<br />
          speed will be a ranking factor for mobile searches too.<br />
          <br />If you're a developer working on a site, now is a good time
          to<br />
          evaluate your performance using our speed tools. Think about how<br />
          performance affects the user experience of your pages and consider<br />
          measuring a variety of real-world user-centric performance metrics.<br /><br />
          Are you shipping too much JavaScript? Too many images? Images<br />
          and JavaScript are the most significant contributors to the page<br />
          weight that affect page load time based on data from HTTP Archive<br />
          and the Chrome User Experience Report - our public dataset for key<br />
          UX metrics as experienced by Chrome users under real-world<br />
          conditions.
        </p>
        <div class="requirements-data__img"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "requirements"
};
</script>

<style lang="scss">
.requirements {
  background-image: url("../assets/imgs/bg-2.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
.requirements-title {
  color: white;
  text-align: center;
  padding-top: 133px;
  margin: 0;
}
.requirements-data {
  padding-bottom: 139px;
}
.requirements-data__text {
  color: #fefefe;
  line-height: 22px;
  padding-left: 30px;
  padding-top: 25px;
}
.requirements-data__img {
  background-image: url("../assets/imgs/man-laptop-v1.svg");
  width: 429px;
  height: 361px;
  margin-left: 53px;
  margin-top: 52px;
}
</style>
