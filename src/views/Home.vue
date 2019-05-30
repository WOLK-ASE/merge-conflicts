<template>
  <div class="home">
    <Header></Header>
    <section1></section1>
    <section2></section2>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import section1 from "@/components/section1.vue";
import section2 from "@/components/section2.vue";

export default {
  name: "home",
  components: {
    Header,
    section1,
    section2
  }
};
</script>
