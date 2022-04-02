<template>
  <div id="app">
    <info-bar />
    <app-jumbotron />
    <services-section />
    <skills-section />
    <partners-section />
    <blog-section />
    <touch-section />
    <app-footer />
  </div>
</template>

<script>
import InfoBar from "./components/InfoBar.vue";
import AppJumbotron from "./components/AppJumbotron.vue";
import ServicesSection from "./components/ServicesSection.vue";
import SkillsSection from "./components/SkillsSection.vue";
import PartnersSection from "./components/PartnersSection.vue";
import BlogSection from "./components/BlogSection.vue";
import TouchSection from "./components/TouchSection.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    InfoBar,
    AppJumbotron,
    ServicesSection,
    SkillsSection,
    PartnersSection,
    BlogSection,
    TouchSection,
    AppFooter,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "./assets/css/variables";
#app {
  font-family: "Inter", sans-serif;
  scroll-behavior: smooth;
  .etichetta {
    color: $blueLagoon;
    font-weight: bold;
    text-transform: uppercase;
  }
  section {
    min-height: 100vh;
  }
}
</style>
