<template>
  <div id="jumbotron">
    <div id="overlay">
      <div class="container h-100 pb-5">
        <AppHeader />
        <div class="row justify-content-end align-items-center h-100">
          <div class="col-6 p-5">
            <h1 class="text-white">Logistic that goes further.</h1>
            <p class="description">
              For 20 years working with the most innovative in the field of
              transport.
            </p>
            <div>
              <a href="" class="btn text-white">GET IN TOUCH</a>
              <button class="btn text-white">READ MORE</button>
            </div>
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
  #overlay {
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.7);
    h1 {
      font-size: 4rem;
      font-weight: 900;
    }
    .description {
      color: #81858aff;
    }
  }
}
</style>
