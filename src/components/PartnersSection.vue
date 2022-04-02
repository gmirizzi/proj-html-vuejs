<template>
  <div id="partners">
    <div class="container">
      <div class="row row-cols-6">
        <div class="col">
          <img src="./../assets/img/logo-5.png" alt="logo" class="opacity-50" />
        </div>
        <div class="col">
          <img src="./../assets/img/logo-1.png" alt="logo" class="opacity-50" />
        </div>
        <div class="col">
          <img src="./../assets/img/logo-2.png" alt="logo" class="opacity-50" />
        </div>
        <div class="col">
          <img src="./../assets/img/logo-3.png" alt="logo" class="opacity-50" />
        </div>
        <div class="col">
          <img src="./../assets/img/logo-4.png" alt="logo" class="opacity-50" />
        </div>
        <div class="col">
          <img src="./../assets/img/logo-5.png" alt="logo" class="opacity-50" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
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
  img {
    height: 25px;
  }
}
</style>
