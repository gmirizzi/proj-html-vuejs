<template>
  <section id="get-in-touch" class="d-flex align-items-center">
    <div class="container">
      <div class="row gx-5">
        <div class="col-8">
          <div class="etichetta">send a message</div>
          <h1 class="fw-bold my-4">
            Get in <span class="py-1 px-3 rounded-2">Touch</span>
          </h1>
          <p class="text-secondary mb-5">
            We will respond to your message as soon as possible.
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
            <button class="btn btn-primary mt-4 text-uppercase">send</button>
          </form>
        </div>
        <div class="col-4">
          <div id="contacts">
            <h2 class="fw-bold fs-5 mb-3">Example Inc.</h2>
            <p class="text-secondary">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit.
            </p>
            <p class="text-secondary">
              Tenetur voluptatem vel adipisci repudiandae, mollitia
              reprehenderit doloremque quisquam est qui voluptatum voluptatibus!
            </p>
            <div id="info" class="mt-">
              <div id="phone" class="d-flex align-items-center">
                <font-awesome-icon
                  class="rounded-circle p-2 me-2"
                  icon="fa-solid fa-phone"
                />
                +1 (305) 1234-5678
              </div>
              <div id="mail" class="d-flex align-items-center my-3">
                <font-awesome-icon
                  class="rounded-circle p-2 me-2"
                  icon="fa-solid fa-envelope"
                />
                hello@example.com
              </div>
              <div id="address" class="d-flex align-items-center">
                <font-awesome-icon
                  class="rounded-circle p-2 me-2"
                  icon="fa-solid fa-location-dot"
                />
                Main Avenue, 987
              </div>
              <a href="#" class="btn btn-outline-primary text-uppercase mt-3"
                >view map</a
              >
            </div>
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
  h1 span {
    background-color: $blueLagoonST;
    color: $blueLagoon;
  }
  input,
  select,
  textarea {
    background-color: #dce2dbff;
  }
  select {
    color: #6c758b;
  }
  textarea {
    height: 150px;
  }
  #info {
    color: $blueLagoon;
    .rounded-circle {
      background-color: $blueLagoonST;
    }
  }
}
</style>
