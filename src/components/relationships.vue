<template>
  <div class="relationsips">
    <div class="container">
      <h2 class="relationsips-title">
        About my relationships with<br />web-development
      </h2>
      <div class="f-s-b relationsips-data">
        <div class="relationsips-data__html">
          <div class="html-img"></div>
          <h3>I'm in love with HTML</h3>
          <p class="m">
            Hypertext Markup Language (HTML) is the<br />
            standard markup language for creating<br />
            web pages and web applications.
          </p>
        </div>
        <div class="relationsips-data__css">
          <div class="css-img"></div>
          <h3>CSS is my best friend</h3>
          <p class="m">
            Cascading Style Sheets (CSS)<br />
            is a style sheet language used for<br />
            describing the presentation of a<br />
            document written in a markup<br />
            language like HTML.
          </p>
        </div>
        <div class="relationsips-data__js">
          <div class="js-img"></div>
          <h3>JavaScript is my passion</h3>
          <p class="m">
            Java-Script is a high-level, interpreted<br />
            programming language.It is a language<br />
            which is also characterized as dynamic,<br />
            weakly typed, prototype-based and<br />
            multi-paradigm.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "relationships"
};
</script>

<style lang="scss">
.relationsips-title {
  text-align: center;
  margin-top: 0px;
  padding-top: 129px;
}
.relationsips-data {
  margin: 10px 30px 0 30px;
  padding-bottom: 120px;
}
.relationsips-data__css {
  margin: 0 73px 0px 40px;
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
.relationsips-data p {
  margin-top: -20px;
  line-height: 22px;
}
</style>
