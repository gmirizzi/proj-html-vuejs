<template>
  <div id="jumbotron">
    <div id="overlay">
      <div class="container h-100">
        <AppHeader />
        <div class="row justify-content-end align-self-center h-100 pt-5">
          <div class="col-6 w-50 px-5">
            <h1 class="text-white">
              <span>
                <div class="rounded-1"></div>
                <span>Logistics</span>
              </span>
              that goes further.
            </h1>
            <p class="description fs-4 my-4">
              For 20 years working with the most innovative in the field of
              transport.
            </p>
            <div>
              <a href="#get-in-touch" class="btn btn-primary text-white me-3"
                >GET IN TOUCH</a
              >
              <button class="btn btn-outline-primary text-white">
                READ MORE
              </button>
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
@import "./../assets/css/_variables.scss";

#jumbotron {
  height: 100vh;
  background-image: url("./../assets/img/jumbo.jpg");
  #overlay {
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.7);
    .container h1 {
      font-size: 4.5rem;
      font-weight: 900;
      span {
        position: relative;
        div {
          background-color: $blueLagoon;
          filter: opacity(50%);
          position: absolute;
          top: 50%;
          left: 5px;
          height: 0.5em;
          width: 100%;
        }
        span {
          position: relative;
          z-index: 1;
        }
      }
    }
    .description {
      color: #919194;
    }
  }
}
</style>
