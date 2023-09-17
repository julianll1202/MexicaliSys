<template>
  <NavBar />
  <body class="index-page">
    <div class="wrapper">
      <WhatWeDo />
      <About />
    </div>
  </body>
  <Footer />
</template>

<script>
import About from "./components/About.vue";
import NavBar from "./components/NavBar.vue";
import WhatWeDo from "./components/WhatWeDo.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    NavBar,
    WhatWeDo,
    About,
    Footer,
  },
};
</script>
<style></style>
