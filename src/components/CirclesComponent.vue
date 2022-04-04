<template>
  <div id="circles-container" class="d-flex flex-wrap">
    <div class="circle rounded-circle" v-for="circle in 36" :key="circle"></div>
  </div>
</template>

<script>
export default {
  name: "CirclesComponent",
};
</script>

<style scoped lang="scss">
@import "./../assets/css/variables";

#circles-container {
  height: 50px;
  width: 100px;
  position: absolute;
  left: 50%;
  top: 0;
  transform: translate(-50%, -50%);
  gap: 8px;
  .circle {
    background-color: $blueLagoon;
    height: 4px;
    width: 4px;
    opacity: 50%;
  }
}
</style>
