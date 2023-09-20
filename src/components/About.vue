<template>
  <div class="section features-6">
    <div class="container">
      <div class="row">
        <div class="col-md-8 mx-auto text-center">
          <span class="badge badge-primary badge-pill mb-3">MXLI SYS</span>
          <h3 class="display-3">About Us</h3>
        </div>
      </div>
      <div class="row align-items-start">
        <div class="col-lg-6">
          <div class="info info-horizontal info-hover-primary">
            <div class="description pl-4">
              <h5 class="title">We develop!</h5>
              <p>
                Experts in the matter of web development, We will always help
                you out achieve what you need at the lowest cost possible and
                always with the best practices and software quality.
              </p>
            </div>
          </div>
          <div class="info info-horizontal info-hover-primary">
            <div class="description pl-4">
              <div v-for="(item, index) in skills" :key="index">
                <ProgressBar :skill="item.skill" :level="item.level" />
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 col-10 mx-md-auto">
          <img
            class="ml-lg-5 about-img"
            src="/img/florian-olivo-4hbJ-eymZ1o-unsplash.jpg"
            c
          />
          <img
            src="/img/mxli_sys_logo.png"
            alt="Logo de Mexicali Systems"
            class="logo"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ProgressBar from "./ProgressBar.vue";

export default {
  setup() {
    let skills = [
      { skill: "Web Development", level: "95" },
      { skill: "Technical Support Efficiency", level: "90" },
      { skill: "HTML5 & CSS3", level: "90" },
      { skill: "Client Satisfaction", level: "100" },
    ];
    return {
      skills,
    };
  },
  components: { ProgressBar },
};
</script>

<style></style>
