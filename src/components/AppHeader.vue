<template>
  <nav class="navbar navbar-expand justify-content-between pt-4">
    <nexgen-brand class="navbar-brand" />
    <div>
      <ul class="navbar-nav me-auto mb-2 mb-lg-0 text-uppercase">
        <li class="nav-item">
          <a class="nav-link text-reset" href="#">HOME</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-reset" href="#services">services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-reset" href="#">skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-reset" href="#">partners</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-reset" href="#">blog</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-reset btn btn-primary" href="#"
            >get in touch</a
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
import NexgenBrand from "./NexgenBrand.vue";

export default {
  name: "AppHeader",
  components: { NexgenBrand },
};
</script>

<style scoped lang="scss">
nav {
  color: #efefeeff;
}
</style>
