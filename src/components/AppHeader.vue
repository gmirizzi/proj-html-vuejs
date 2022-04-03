<template>
  <nav class="navbar navbar-expand justify-content-between pt-4">
    <nexgen-brand class="navbar-brand" />
    <div>
      <ul class="navbar-nav me-auto mb-2 mb-lg-0 text-uppercase">
        <li v-for="item in arrLinks" :key="item.name" class="nav-item">
          <a class="nav-link text-reset" :href="item.link">{{ item.name }}</a>
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
  data() {
    return {
      arrLinks: [
        {
          name: "home",
          link: "",
        },
        {
          name: "serivices",
          link: "#services",
        },
        {
          name: "skills",
          link: "#skills",
        },
        {
          name: "partners",
          link: "#partners",
        },
        {
          name: "blog",
          link: "#blog",
        },
        {
          name: "get in touch",
          link: "#get-in-touch",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
nav {
  color: #efefeeff;
}
</style>
