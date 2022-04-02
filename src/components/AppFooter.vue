<template>
  <footer class="pt-5 text-white">
    <div class="container py-5">
      <div class="row">
        <div class="col-4">
          <div id="contacts">
            <h1>NEXGEN</h1>
            <P
              >Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet
              minus labore quo consequatur voluptatibus saepe et dolorum,
              architecto rem ab obcaecati nihil, nostrum distinctio velit odio
              quos itaque porro nulla!</P
            >
          </div>
        </div>
        <div class="col-8">
          <div class="row">
            <div class="col-4">
              <div class="overlay h-100 w-100 p-4 rounded-3">
                <h2>section</h2>
                <ul>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="overlay h-100 w-100 p-4 rounded-3">
                <h2>section</h2>
                <ul>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="overlay h-100 w-100 p-4 rounded-3">
                <h2>section</h2>
                <ul>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                  <li><a href="">link</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer-bar />
  </footer>
</template>

<script>
import FooterBar from "./FooterBar.vue";
export default {
  components: { FooterBar },
  name: "AppFooter",
};
</script>

<style lang="scss" scoped>
footer {
  background-image: url("./../assets/img/bg-10.jpg");
  background-position: center;
  background-size: cover;
  .overlay {
    background-color: rgba(0, 0, 0, 0.2);
  }
}
</style>
