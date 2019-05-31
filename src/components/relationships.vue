<template>
  <div class="relationsips">
    <div class="container"></div>
    <div class="relationsips-title2 h2">
      About my relationships with<br />web-development
    </div>
    <div class="f-j-c relationsips-data2">
      <div class="relationsips-data2__html">
        <div class="html-img"></div>
        <div class="h3">I'm in love with HTML</div>
        <p class="medium">
          Hypertext Markup Language (HTML) is the<br />
          standard markup language for creating<br />
          web pages and web applications.
        </p>
      </div>
      <div class="relationsips-data2__css">
        <div class="css-img"></div>
        <div class="h3">CSS is my best friend</div>
        <p class="medium">
          Cascading Style Sheets (CSS)<br />
          is a style sheet language used for<br />
          describing the presentation of a<br />
          document written in a markup<br />
          language like HTML.
        </p>
      </div>
      <div class="relationsips-data2__js">
        <div class="js-img"></div>
        <div class="h3">JavaScript is my passion</div>
        <p class="medium">
          Java-Script is a high-level, interpreted<br />
          programming language.It is a language<br />
          which is also characterized as dynamic,<br />
          weakly typed, prototype-based and<br />
          multi-paradigm.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "relationships"
};
</script>

<style>
.relationsips {
  padding-top: 129px;
}
.relationsips-title2 {
  margin: auto;
  text-align: center;
  margin-bottom: 51px;
}
.relationsips-data2__css {
  margin: 0 73px 140px 40px;
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
