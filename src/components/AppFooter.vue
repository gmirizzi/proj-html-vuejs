<template>
  <footer class="pt-5">
    <div class="container py-5">
      <div class="row gx-5">
        <div class="col-4 text-secondary pe-5">
          <div id="contacts">
            <nexgen-brand class="mb-5" />
            <P class="my-4"
              >A Functional HTML Template for Corporate & Business</P
            >
            <div id="phone" class="d-flex align-items-center">
              <font-awesome-icon class="me-2" icon="fa-solid fa-phone" />
              +1 (305) 1234-5678
            </div>
            <div id="mail" class="d-flex align-items-center my-3">
              <font-awesome-icon class="me-2" icon="fa-solid fa-envelope" />
              hello@example.com
            </div>
            <div id="address" class="d-flex align-items-center">
              <font-awesome-icon class="me-2" icon="fa-solid fa-location-dot" />
              Main Avenue, 987
            </div>
            <a
              href="#get-in-touch"
              class="btn btn-outline-primary text-uppercase text-white mt-4"
              >get in touch</a
            >
          </div>
        </div>
        <div class="col-8">
          <div class="row">
            <div class="col-4">
              <div class="overlay h-100 w-100 p-4 rounded-3">
                <h2 class="fs-4 fw-bold text-white">section</h2>
                <ul>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="overlay h-100 w-100 p-4 rounded-3">
                <h2 class="fs-4 fw-bold text-white">section</h2>
                <ul>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="overlay h-100 w-100 p-4 rounded-3">
                <h2 class="fs-4 fw-bold text-white">section</h2>
                <ul>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li><a class="text-secondary" href="">link</a></li>
                  <li class="text-secondary">
                    <a class="ms-2 text-reset text-decoration-none" href=""
                      >Information</a
                    >
                  </li>
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
import NexgenBrand from "./NexgenBrand.vue";

export default {
  components: { NexgenBrand, FooterBar },
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
    li::marker {
      content: ">";
      font-size: 1.5em;
    }
  }
}
</style>
