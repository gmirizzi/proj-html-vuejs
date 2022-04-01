<template>
  <div id="app">
    <InfoBar />
  </div>
</template>

<script>
import InfoBar from "./components/InfoBar.vue";

export default {
  name: "App",
  components: {
    InfoBar,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
</style>
