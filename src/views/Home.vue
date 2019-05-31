<template>
  <div class="home">
    <Header></Header>
    <banner></banner>
    <acquaintance></acquaintance>
    <relationships></relationships>
    <requirements></requirements>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import banner from "@/components/banner.vue";
import acquaintance from "@/components/acquaintance.vue";
import relationships from "@/components/relationships.vue";
import requirements from "@/components/requirements.vue";

export default {
  name: "home",
  components: {
    Header,
    banner,
    acquaintance,
    relationships,
    requirements
  }
};
</script>
