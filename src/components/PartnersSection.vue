<template>
  <div id="partners">
    <circles-component />
    <div class="container">
      <div class="row row-cols-6">
        <div class="col">
          <a href="#">
            <img
              src="./../assets/img/logo-5.png"
              alt="logo"
              class="opacity-50"
            />
          </a>
        </div>
        <div class="col">
          <a href="#">
            <img
              src="./../assets/img/logo-1.png"
              alt="logo"
              class="opacity-50"
            />
          </a>
        </div>
        <div class="col">
          <a href="#">
            <img
              src="./../assets/img/logo-2.png"
              alt="logo"
              class="opacity-50"
            />
          </a>
        </div>
        <div class="col">
          <a href="#">
            <img
              src="./../assets/img/logo-3.png"
              alt="logo"
              class="opacity-50"
            />
          </a>
        </div>
        <div class="col">
          <a href="#">
            <img
              src="./../assets/img/logo-4.png"
              alt="logo"
              class="opacity-50"
            />
          </a>
        </div>
        <div class="col">
          <a href="#">
            <img
              src="./../assets/img/logo-5.png"
              alt="logo"
              class="opacity-50"
            />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import CirclesComponent from "./CirclesComponent.vue";
export default {
  components: { CirclesComponent },
  name: "PartnersSection",
};
</script>

<style lang="scss">
@import "./../assets/css/_variables.scss";

#partners {
  height: 200px;
  display: flex;
  align-items: center;
  background-color: $saltpan;
  position: relative;
  img {
    height: 25px;
  }
}
</style>
