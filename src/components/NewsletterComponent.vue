<template>
  <div id="newsletter" class="py-5">
    <div class="container p-5">
      <div class="row">
        <div class="col-6">
          <div class="etichetta">newsletter</div>
          <h1 class="text-white fw-bold">Know First</h1>
          <p class="text-secondary">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore
            eligendi dolore veritatis ut dolorem est inventore unde nam laborum
            consequatur repellat libero accusantium reiciendis, illo molestias
            quasi saepe. Ducimus, nemo.
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
            <a href="#" class="btn text-white text-uppercase">subscribe</a>
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
#newsletter {
  background-image: url("./../assets/img/bg-1.jpg");
  background-position: center;
  background-size: cover;
}
</style>
