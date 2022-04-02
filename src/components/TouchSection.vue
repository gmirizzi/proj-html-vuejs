<template>
  <section id="get-in-touch" class="d-flex align-items-center">
    <div class="container">
      <div class="row">
        <div class="col-8">
          <div class="etichetta">send a message</div>
          <h1 class="fw-bold">Get in Touch</h1>
          <p class="text-secondary">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi
            quibusdam quidem accusamus vitae magni quas illum consequuntur
            fugiat dignissimos quasi ipsa, cum numquam voluptatem minus aut vel
            temporibus non. Autem.
          </p>
          <form>
            <div class="row gy-3">
              <div class="col-6">
                <input type="text" class="form-control" placeholder="Name" />
              </div>
              <div class="col-6">
                <input type="email" class="form-control" placeholder="Email" />
              </div>
              <div class="col-6">
                <input type="tel" class="form-control" placeholder="Phone" />
              </div>
              <div class="col-6">
                <select class="form-select">
                  <option selected>More info</option>
                </select>
              </div>
              <div class="col">
                <textarea class="form-control" placeholder="Message"></textarea>
              </div>
            </div>
            <button class="btn text-uppercase">send</button>
          </form>
        </div>
        <div class="col-4">
          <div id="contacts">
            <h2>Example Inc.</h2>
            <p class="text-secondary">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              Provident amet doloremque consectetur, at ut voluptate corrupti,
              rem officiis dolorum dolorem natus vitae labore modi in
              repudiandae nisi enim et hic?
            </p>
            <p class="text-secondary">
              Tenetur voluptatem vel adipisci repudiandae, mollitia
              reprehenderit doloremque quisquam est qui voluptatum voluptatibus!
              Temporibus ducimus consequatur adipisci deserunt quidem. Nihil eos
              distinctio maxime provident rerum excepturi ullam, quas doloremque
              illum.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TouchSection",
};
</script>

<style lang="scss">
@import "./../assets/css/_variables.scss";

#get-in-touch {
  background-color: $saltpan;
}
</style>
