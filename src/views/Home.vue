<template>
  <div class="home">
    <Yichun />
    <About />
    <ProjectCards />
    <Footerr />
  </div>
</template>

<script>
// @ is an alias to /src
import Yichun from "@/views/Yichun.vue";
import About from "@/views/About.vue";
import ProjectCards from "../components/ProjectCards.vue";
import Footerr from "@/views/Footerr.vue";


export default {
  name: "Home",
  components: {
    Yichun, About, ProjectCards, Footerr
  }
};
</script>

<style>
  
</style>