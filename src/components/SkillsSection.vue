<template>
  <section id="skills" class="text-white py-5">
    <div class="container">
      <div class="row">
        <div class="col-6 pe-5">
          <div class="etichetta text-uppercase">about the network</div>
          <h1 class="fw-bold my-4">
            <span class="py-1 px-3 rounded-2">The</span> Company
          </h1>
          <p class="text-secondary mb-5">
            With all of this expertise and capability comes an unrivalled
            commitment to customer service.
          </p>
          <div class="skill d-flex">
            <div class="row">
              <div class="col-2">
                <div class="circle-wrap rounded-circle bg-dark">
                  <div
                    class="inside-circle d-flex justify-content-center align-items-center"
                  >
                    0<small>%</small>
                  </div>
                  <div class="circle">
                    <div class="mask">
                      <div class="fill"></div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-10 px-5">
                <div>
                  <h2>Leadership</h2>
                  <p class="text-secondary">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="skill d-flex my-3">
            <div class="row">
              <div class="col-2">
                <div class="circle-wrap rounded-circle bg-dark">
                  <div
                    class="inside-circle d-flex justify-content-center align-items-center"
                  >
                    0<small>%</small>
                  </div>
                  <div class="circle">
                    <div class="mask">
                      <div class="fill"></div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-10 px-5">
                <div>
                  <h2>Psychology</h2>
                  <p class="text-secondary">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="skill d-flex">
            <div class="row">
              <div class="col-2">
                <div class="circle-wrap rounded-circle bg-dark">
                  <div
                    class="inside-circle d-flex justify-content-center align-items-center"
                  >
                    1<small>%</small>
                  </div>
                  <div class="circle">
                    <div class="mask">
                      <div class="fill"></div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-10 px-5">
                <div>
                  <h2>Flexibility</h2>
                  <p class="text-secondary">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
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
  name: "SkillsSection",
};
</script>

<style scoped lang="scss">
@import "./../assets/css/_variables.scss";

section {
  background-image: url("./../assets/img/about-5.jpg");
  background-position: right 0% bottom 50%;
  background-size: 50%;
  background-repeat: no-repeat;
  background-color: #111117ff;
  h1 span {
    background-color: $blueLagoonST;
  }
}
.skill {
  h2 {
    font-size: 1.5rem;
  }
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
    clip: rect(0px, 0, 0, 0px);
    background-color: $blueLagoon;
  }
  .inside-circle {
    width: 4em;
    height: 4em;
    margin-top: 0.5em;
    margin-left: 0.5em;
    border-radius: 50%;
    background-color: #111117ff;
    position: absolute;
    z-index: 1;
  }
}
.skill:last-child {
  .mask .fill {
    clip: rect(2.4em, 1em, 2.5em, 0em);
    background-color: $blueLagoon;
  }
}
</style>
