<template>
  <div>
    <Header />
    <!-- hero-section -->
    <section class="hero-section inner-banner">
      <div class="container">
        <img class="dark-dot" src="../../assets/images/circle-shap.png" />
        <div class="row">
          <div class="col">
            <h1 data-aos="fade-down" data-aos-easing="linear" data-aos-duration="600">
              OUR CLIENTS
            </h1>
            <p data-aos="fade-right" data-aos-easing="linear" data-aos-duration="600">
              Our diversified digital portfolio meet kind of your needs. The work will be
              done according to your instructions which will surely meet your level of
              satisfaction and expectations.
            </p>
            <div class="newletter">
              <img class="roll" src="../../assets/images/roll.png" />
            </div>
            <img class="c-shap" src="../../assets/images/angle.png" />
          </div>
          <div class="col">
            <div class="hero-img">
              <img src="../../assets/images/Client.gif" id="client-hero" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Project -->

    <div class="client-brand-portfolio">
      <div class="container">
        <img class="u-shap" src="../../assets/images/u-angle.png" />
        <div class="title-style project-title">
          <span class="brand">Our Work</span>
          <h2 class="brand-title">OUR PORTFOLIO</h2>
        </div>
        <div class="row">
          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/first.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/second.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/Third.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/fourth.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/Fivth_logo.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/Sixth.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/true.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/Evth.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/Nine.png" alt="" />
            </div>
          </div>

          <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
            <div
              class="logo-img"
              data-aos="zoom-in-down"
              data-aos-easing="linear"
              data-aos-duration="600"
            >
              <img src="../../assets/images/last_img.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <OurTestimonials />
    <Footer2 />
  </div>
</template>

<script>
import Header from "./Header.vue";
import OurTestimonials from "./OurTestimonials.vue";
import Footer2 from "./Footer2.vue";
export default {
  name: "Clientpage",
  components: {
    Header,
    OurTestimonials,
    Footer2,
  },
};
</script>

