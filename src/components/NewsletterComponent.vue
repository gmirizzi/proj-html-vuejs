<template>
  <div id="newsletter" class="py-5">
    <div class="container p-5">
      <div class="row">
        <div class="col-6">
          <div class="etichetta">newsletter</div>
          <h1 class="text-white fw-bold my-4">
            <span class="py-1 px-3 rounded-2">Know</span> First
          </h1>
          <p class="text-secondary">
            Follow closely and receive content about our company and the news of
            the current market.
          </p>
        </div>
        <div class="col-6 pe-5">
          <form>
            <div class="mb-3">
              <input type="text" class="form-control" placeholder="Name" />
            </div>
            <div class="mb-3">
              <input type="email" class="form-control" placeholder="Email" />
            </div>
            <a href="#" class="btn btn-primary text-white text-uppercase"
              >subscribe</a
            >
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewsletterComponent",
};
</script>

<style lang="scss" scoped>
@import "./../assets/css/_variables.scss";

#newsletter {
  background-image: url("./../assets/img/bg-1.jpg");
  background-position: center;
  background-size: cover;
  h1 span {
    background-color: $blueLagoonST;
  }
  input {
    background-color: rgba(255, 255, 255, 0.5);
  }
}
</style>
