<template>
  <div id="jumbotron">
    <div class="container">
      <AppHeader />
      <div class="row justify-content-end mt-5">
        <div class="col-6 p-5">
          <h1 class="fw-bolder text-white">Logistic that goes further.</h1>
          <p class="text-secondary">
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
  height: calc(100vh - 56px);
  background-image: url("./../assets/img/jumbo.jpg");
}
</style>
