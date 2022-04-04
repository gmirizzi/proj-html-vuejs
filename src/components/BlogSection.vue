<template>
  <section id="blog" class="pt-5">
    <div class="container py-5">
      <div class="etichetta">our editorial content</div>
      <h1 class="fw-bold my-4">
        Latest <span class="py-1 px-3 rounded-2">News</span>
      </h1>
      <div class="d-flex justify-content-between align-items-center mb-5">
        <p class="text-secondary">
          Every week we publish content about what is best in the business
          world.
        </p>
        <button class="btn btn-primary text-uppercase">See All</button>
      </div>
      <div class="row row-cols-3 pb-5">
        <div class="col">
          <div class="card border-0 bg-dark text-white">
            <img
              src="./../assets/img/news-1.jpg"
              class="card-img opacity-50"
              alt="..."
            />
            <div
              class="card-img-overlay pb-5 px-4 d-flex align-items-end text-center"
            >
              <p class="card-text fw-bold">
                This is a wider card with supporting text below as a natural
                lead-in to additional content. This content is a little bit
                longer.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card border-0 bg-dark text-white">
            <img
              src="./../assets/img/news-2.jpg"
              class="card-img opacity-50"
              alt="..."
            />
            <div
              class="card-img-overlay pb-5 px-4 d-flex align-items-end text-center"
            >
              <p class="card-text fw-bold">
                This is a wider card with supporting text below as a natural
                lead-in to additional content. This content is a little bit
                longer.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card border-0 bg-dark text-white">
            <img
              src="./../assets/img/news-3.jpg"
              class="card-img opacity-50"
              alt="..."
            />
            <div
              class="card-img-overlay pb-5 px-4 d-flex align-items-end text-center"
            >
              <p class="card-text fw-bold">
                This is a wider card with supporting text below as a natural
                lead-in to additional content. This content is a little bit
                longer.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <newsletter-component />
  </section>
</template>

<script>
import NewsletterComponent from "./NewsletterComponent.vue";
export default {
  components: { NewsletterComponent },
  name: "BlogSection",
};
</script>

<style scoped lang="scss">
@import "./../assets/css/_variables.scss";

h1 span {
  background-color: $blueLagoonST;
  color: $blueLagoon;
}
.card,
.card-img {
  border-radius: 1rem;
}
</style>
