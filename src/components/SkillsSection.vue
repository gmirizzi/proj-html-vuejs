<template>
  <section id="skills" class="bg-dark text-white py-5">
    <div class="container">
      <div class="row">
        <div class="col-6">
          <div class="etichetta text-uppercase">about the network</div>
          <h1>The Company</h1>
          <p class="text-secondary">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus
            quod, repudiandae consequatur cumque ullam corrupti error debitis
            non fugit odio, molestiae, esse nisi laborum laboriosam aut nesciunt
            recusandae distinctio repellendus?
          </p>
          <div class="skill d-flex">
            <div class="circle">%</div>
            <div>
              <h2>skill</h2>
              <p>descrizione</p>
            </div>
          </div>
          <div class="skill d-flex">
            <div class="circle">%</div>
            <div>
              <h2>skill</h2>
              <p>descrizione</p>
            </div>
          </div>
          <div class="skill d-flex">
            <div class="circle">%</div>
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

<style scoped>
section {
  background-image: url("./../assets/img/about-5.jpg");
  background-position: right 0% bottom 50%;
  background-size: 50%;
  background-repeat: no-repeat;
}
</style>
