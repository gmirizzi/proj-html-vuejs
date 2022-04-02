<template>
  <section id="blog">
    <div class="container py-5">
      <div class="etichetta">our editorial content</div>
      <h1>Latest News</h1>
      <div class="d-flex justify-content-between">
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consequuntur
          voluptatem nesciunt ad voluptates, dolore quibusdam mollitia
          voluptatum quos temporibus vel nam alias! Laudantium necessitatibus
          numquam, quae debitis eius eos voluptatibus.
        </p>
        <button class="btn">See All</button>
      </div>
      <div class="row row-cols-3">
        <div class="col">
          <div class="card bg-dark text-white">
            <img
              src="./../assets/img/news-1.jpg"
              class="card-img opacity-50"
              alt="..."
            />
            <div class="card-img-overlay d-flex align-items-end text-center">
              <p class="card-text fw-bold">
                This is a wider card with supporting text below as a natural
                lead-in to additional content. This content is a little bit
                longer.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card bg-dark text-white">
            <img
              src="./../assets/img/news-2.jpg"
              class="card-img opacity-50"
              alt="..."
            />
            <div class="card-img-overlay d-flex align-items-end text-center">
              <p class="card-text fw-bold">
                This is a wider card with supporting text below as a natural
                lead-in to additional content. This content is a little bit
                longer.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card bg-dark text-white">
            <img
              src="./../assets/img/news-3.jpg"
              class="card-img opacity-50"
              alt="..."
            />
            <div class="card-img-overlay d-flex align-items-end text-center">
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

<style></style>
