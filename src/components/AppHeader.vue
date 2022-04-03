<template>
  <nav class="navbar navbar-expand justify-content-between pt-4">
    <nexgen-brand class="navbar-brand" />
    <div>
      <ul class="navbar-nav me-auto mb-2 mb-lg-0 text-uppercase">
        <li v-for="item in arrLinks" :key="item.name" class="nav-item px-3">
          <a :class="item.class" :href="item.link">{{ item.name }}</a>
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
          class: "nav-link text-reset",
        },
        {
          name: "serivices",
          link: "#services",
          class: "nav-link text-reset",
        },
        {
          name: "skills",
          link: "#skills",
          class: "nav-link text-reset",
        },
        {
          name: "partners",
          link: "#partners",
          class: "nav-link text-reset",
        },
        {
          name: "blog",
          link: "#blog",
          class: "nav-link text-reset",
        },
        {
          name: "get in touch",
          link: "#get-in-touch",
          class: "nav-link text-reset btn-primary rounded-1 px-4",
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
