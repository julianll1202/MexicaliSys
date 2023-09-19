<template>
  <body class="index-page">
    <NavBar />
    <HeroSection />
    <div class="wrapper">
      <WhatWeDo />
      <About />
      <Contact />
    </div>
    <Footer />
  </body>
</template>

<script>
import About from "./components/About.vue";
import NavBar from "./components/NavBar.vue";
import WhatWeDo from "./components/WhatWeDo.vue";
import Footer from "./components/Footer.vue";
import Contact from "./components/Contact.vue";
import HeroSection from "./components/HeroSection.vue";

export default {
  name: "App",
  components: {
    NavBar,
    HeroSection,
    WhatWeDo,
    About,
    Contact,
    Footer,
  },
};
</script>
<style></style>
