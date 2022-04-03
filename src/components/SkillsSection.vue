<template>
  <section id="skills" class="text-white py-5">
    <div class="container">
      <div class="row">
        <div class="col-6">
          <div class="etichetta text-uppercase">about the network</div>
          <h1 class="fw-bold my-3">The Company</h1>
          <p class="text-secondary">
            With all of this expertise and capability comes an unrivalled
            commitment to customer service.
          </p>
          <div class="skill d-flex">
            <div class="circle-wrap rounded-circle bg-dark">
              <div
                class="inside-circle d-flex justify-content-center align-items-center"
              >
                75%
              </div>
              <div class="circle">
                <div class="mask">
                  <div class="fill"></div>
                </div>
              </div>
            </div>
            <div>
              <h2>skill</h2>
              <p>descrizione</p>
            </div>
          </div>
          <div class="skill d-flex">
            <div class="circle-wrap"></div>
            <div>
              <h2>skill</h2>
              <p>descrizione</p>
            </div>
          </div>
          <div class="skill d-flex">
            <div class="circle-wrap"></div>
            <div>
              <h2>skill</h2>
              <p>descrizione</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SkillsSection",
};
</script>

<style scoped lang="scss">
section {
  background-image: url("./../assets/img/about-5.jpg");
  background-position: right 0% bottom 50%;
  background-size: 50%;
  background-repeat: no-repeat;
  background-color: #111117ff;
}
.circle-wrap {
  height: 5em;
  width: 5em;
  .circle .mask,
  .circle .fill {
    width: 5em;
    height: 5em;
    position: absolute;
    border-radius: 50%;
  }
  .mask .fill {
    clip: rect(0px, 2.5em, 5em, 0px);
    background-color: #227ded;
  }
  .inside-circle {
    width: 4.5em;
    height: 4.5em;
    margin-top: 0.25em;
    margin-left: 0.25em;
    border-radius: 50%;
    color: #1e51dc;
    background-color: #111117ff;
    position: absolute;
    z-index: 1;
  }
}
</style>
