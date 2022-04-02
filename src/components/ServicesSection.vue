<template>
  <section id="services" class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-4">
          <div class="etichetta text-uppercase">our business area</div>
          <h1 class="fw-bolder">Logistic services</h1>
          <p class="text-secondary">
            We are leaders in providing logistics services whit a set of cutting
            edge technologies and a team of experienced and renowed
            professionales
          </p>
          <div>
            <button class="btn">Tradition</button
            ><button class="btn">Quality</button
            ><button class="btn">Security</button>
          </div>
          <button class="btn text-uppercase">read more</button>
        </div>
        <div class="col-8">
          <div class="row">
            <div class="col-6">
              <div class="card p-4">
                <img
                  src="./../assets/img/gallery-3.jpg"
                  class="card-img-top"
                  alt="..."
                />
                <div class="card-body">
                  <h5 class="card-title">Tecnlogy</h5>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-6">
              <div class="card p-4">
                <img
                  src="./../assets/img/gallery-5.jpg"
                  class="card-img-top"
                  alt="..."
                />
                <div class="card-body">
                  <h5 class="card-title">Transport</h5>
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
#services {
  background-color: #eef4edff;
}
</style>
