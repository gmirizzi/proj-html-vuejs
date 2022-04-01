<template>
  <div id="app">
    <InfoBar />
    <AppJumbotron />
  </div>
</template>

<script>
import InfoBar from "./components/InfoBar.vue";
import AppJumbotron from "./components/AppJumbotron.vue";

export default {
  name: "App",
  components: {
    InfoBar,
    AppJumbotron,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
</style>
