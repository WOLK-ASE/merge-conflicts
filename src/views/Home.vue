<template>
  <div class="home">
    <Header></Header>
    <banner></banner>
    <acquaintance></acquaintance>
    <relationships></relationships>
    <requirements></requirements>
    <users></users>
    <footer></footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import banner from "@/components/banner.vue";
import acquaintance from "@/components/acquaintance.vue";
import relationships from "@/components/relationships.vue";
import requirements from "@/components/requirements.vue";
import users from "@/components/users.vue";
import footer from "@/components/footer.vue";

export default {
  name: "home",
  components: {
    Header,
    banner,
    acquaintance,
    relationships,
    requirements,
    users,
    footer
  }
};
</script>
