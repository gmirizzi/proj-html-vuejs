<template>
  <div id="jumbotron">
    <div class="container">
      <AppHeader />
      <div class="row justify-content-end">
        <div class="col-6">
          <h1>Logistic that goes further.</h1>
          <p>
            For 20 years working with the most innovative in the field of
            transport.
          </p>
          <div>
            <a href="">GET IN TOUCH</a>
            <a href="">READ MORE</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AppHeader from "./AppHeader.vue";

export default {
  name: "AppJumbotron",
  components: {
    AppHeader,
  },
};
</script>

<style lang="scss" scoped>
#jumbotron {
  height: 1000px;
  background-image: url("./../assets/img/jumbo.jpg");
}
</style>
