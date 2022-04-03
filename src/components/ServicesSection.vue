<template>
  <section id="services" class="py-5 d-flex align-items-center">
    <div class="container">
      <div class="row">
        <div class="col-4 pe-4">
          <div class="etichetta text-uppercase">our business area</div>
          <h1 class="fw-bolder my-3">Logistics services</h1>
          <p class="text-secondary pb-2">
            We are leaders in providing logistics services whit a set of cutting
            edge technologies and a team of experienced and renowed
            professionales
          </p>
          <div id="services-btns" class="my-2">
            <button class="btn">Tradition</button
            ><button class="btn">Quality</button
            ><button class="btn">Security</button>
          </div>
          <button class="btn btn-primary text-uppercase mt-3">read more</button>
        </div>
        <div class="col-8">
          <div class="row">
            <div class="col-6">
              <div class="card p-5">
                <img
                  src="./../assets/img/gallery-3.jpg"
                  class="card-img-top"
                  alt="..."
                />
                <div class="card-body">
                  <h5 class="card-title fw-bold fs-3 my-3">Tecnology</h5>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-6">
              <div class="card p-5">
                <img
                  src="./../assets/img/gallery-5.jpg"
                  class="card-img-top"
                  alt="..."
                />
                <div class="card-body">
                  <h5 class="card-title fw-bold fs-3 my-3">Transport</h5>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ServicesSection",
};
</script>

<style lang="scss" scoped>
@import "./../assets/css/_variables.scss";

#services {
  background-color: #eef4edff;
  .card {
    border-radius: 1em;
    border: none;
  }
  #services-btns {
    .btn {
      background-color: #cce3deff;
      color: $blueLagoon;
      padding-left: 0.5em;
      padding-right: 0.5em;
      margin-right: 1em;
    }
  }
}
</style>
