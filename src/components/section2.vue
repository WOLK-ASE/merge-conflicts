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
          <p class="section2-data__text medium">
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
      <div class="relations">
        <div class="section2-title2 h2">
          About my relationships with<br />web-development
        </div>
        <div class="f-j-c section2-data2">
          <div class="section2-data2__html">
            <div class="html-img"></div>
            <div class="h3">I'm in love with HTML</div>
            <p class="medium">
              Hypertext Markup Language (HTML) is the<br /> standard markup language
              for creating<br /> web pages and web applications.
            </p>
          </div>
          <div class="section2-data2__css">
            <div class="css-img"></div>
            <div class="h3">CSS is my best friend</div>
            <p class="medium">
              Cascading Style Sheets (CSS)<br /> is a style sheet language used for<br />
              describing the presentation of a<br /> document written in a markup<br />
              language like HTML.
            </p>
          </div>
          <div class="section2-data2__js">
            <div class="js-img"></div>
            <div class="h3">JavaScript is my passion</div>
            <p class="medium">
              Java-Script is a high-level, interpreted<br /> programming language.It
              is a language<br /> which is also characterized as dynamic,<br /> weakly
              typed, prototype-based and<br /> multi-paradigm.
            </p>
          </div>
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
.relations {
  padding-top: 129px;
}
.section2-title2 {
  margin: auto;
  text-align: center;
  margin-bottom: 51px;
}
.section2-data2__css {
  margin: 0 73px 0 40px;

}
.html-img {
  background-image: url("../assets/imgs/html.svg");
  width: 98px;
  height: 111px;
  margin-bottom: 28px;
}
.css-img {
  background-image: url("../assets/imgs/css.svg");
  width: 98px;
  height: 111px;
  margin-bottom: 28px;
}
.js-img {
  background-image: url("../assets/imgs/javascript.svg");
  width: 98px;
  height: 111px;
  margin-bottom: 28px;
}
</style>
