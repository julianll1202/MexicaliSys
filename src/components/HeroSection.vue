<template>
  <div class="section section-hero section-shaped">
    <div class="page-header">
      <img
        src="/img/fotis-fotopoulos-DuHKoV44prg-unsplash.jpg"
        style="width: 100vw"
        class="img-fluid"
      />
      <div class="hero-logo">
        <img src="/img/mxli_sys_logo.png" />
        <h3>
          <span class="badge text-uppercase badge-primary"
            >Custom Software</span
          >

          <span class="badge text-uppercase badge-success"
            >Technical Support</span
          >

          <span class="badge text-uppercase badge-danger">Consulting</span>

          <span class="badge text-uppercase badge-warning">Networking</span>
        </h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.section-hero {
  width: 100vw;
  height: auto;
  max-height: 400px;
}

.badge {
  margin-right: 10px;
}
.hero-logo {
  z-index: 3;
  position: relative;
  top: -900px;
  left: 0;
  font-weight: bold;
  color: white;
  text-align: center;
  text-transform: capitalize;
}
.hero-logo > h3 {
  color: white;
  font-weight: bold;
}
.hero-logo > img {
  width: 250px;
  height: 250px;
  margin-bottom: 0;
}
</style>
