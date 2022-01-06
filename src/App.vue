<template>
  <div id="app">
    <router-view></router-view>
    <!-- <carousel /> -->
  </div>
</template>

<script>
// import carousel  from './components/slider.vue';
// import Footer  from './components/Footer.vue';
// import sliderbanner from './components/sliderbanner.vue';
// import clients from './components/clients.vue';
// import Brand from './components/Branding.vue';
// import values from './components/values.vue';
// import project from './components/Projects.vue'
// import  skillsTestimonial from './components/skillsTestimonial.vue';
// import  testimonial from './components/testimonial.vue';
// import About  from './components/About.vue';
// import './assets/js/custom.js';

export default {
  name: "app",
  components: {
    // carousel
    // Footer,sliderbanner,
    // clients,Brand,values,
    // project,skillsTestimonial,
    // testimonial,About
  },

  // methods: {
  //   gotoHome() {
  //     let route = this.$router.resolve({ path: "/" });
  //     window.open(route.href);
  //   },
  //   gotoAbout() {
  //     let route = this.$router.resolve({ path: "/About" });
  //     window.open(route.href, "_blank");
  //   },

  //   gotoServices() {
  //     let route = this.$router.resolve({ path: "/Services" });
  //     window.open(route.href, "_blank");
  //   },
  //   gotoProjects() {
  //     let route = this.$router.resolve({ path: "/Projects" });
  //     window.open(route.href, "_blank");
  //   },
  //   gotoClients() {
  //     let route = this.$router.resolve({ path: "/Clients" });
  //     window.open(route.href, "_blank");
  //   },
  //   gotoContact() {
  //     let route = this.$router.resolve({ path: "/Contact" });
  //     window.open(route.href, "_blank");
  //   },
  // },
};
</script>

<style scoped>
@import "https://fonts.googleapis.com";
@import "https://fonts.gstatic.com";
@import "https://fonts.googleapis.com/css2?family=Exo+2:wght@100;200;300;400;500;600;700;800&display=swap";
@import "https://fonts.googleapis.com";
@import "./assets/css/style.css";
@import url("https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css");
/* @import url("./assets/css/bootstrap.min.css"); */
@import "../node_modules/slick-carousel/slick/slick.css";
</style>
