<template>
  <div>
    <!-- services -->
    <section class="service">
      <div class="container">
        <img class="tablet" src="../../assets/images/tablat-circle.png" />
        <div class="title-style">
          <span
            class="brand"
            data-aos="fade-down"
            data-aos-easing="linear"
            data-aos-duration="600"
            >Our Services</span
          >
          <h2
            class="brand-title"
            data-aos="fade-down"
            data-aos-easing="linear"
            data-aos-duration="400"
          >
            Branding Services
          </h2>
          <router-link
            to="/services"
            data-aos="fade-down"
            data-aos-easing="linear"
            data-aos-duration="1000"
          >
            All Services</router-link
          >
          <p>
            The work will be done according to your instructions which will surely meet
            your level of satisfaction and expectations.
          </p>
        </div>
        <div class="row">
          <div class="col-3" data-aos="flip-left" data-aos-duration="1000">
            <div class="service-box">
              <div class="service-img">
                <img src="../../assets/images/Mobile Application.png" />
              </div>
              <h3>Mobile Application</h3>
            </div>
          </div>
          <div
            class="col-3"
            data-aos="flip-left"
            data-aos-easing="ease-out-cubic"
            data-aos-duration="1000"
          >
            <div class="service-box">
              <div class="service-img">
                <img src="../../assets/images/Website Development.png" />
              </div>
              <h3>Website Development</h3>
            </div>
          </div>
          <div
            class="col-3"
            data-aos="flip-left"
            data-aos-easing="ease-out-cubic"
            data-aos-duration="1000"
          >
            <div class="service-box">
              <div class="service-img">
                <img src="../../assets/images/Logo & Branding.png" />
              </div>
              <h3>Logo & Branding</h3>
            </div>
          </div>
          <div
            class="col-3"
            data-aos="flip-left"
            data-aos-easing="ease-out-cubic"
            data-aos-duration="1000"
          >
            <div class="service-box">
              <div class="service-img">
                <img src="../../assets/images/Digital Meting.png" />
              </div>
              <h3>Digital Marketing</h3>
            </div>
          </div>
        </div>
        <img class="ball" src="../../assets/images/ball.png" />
      </div>
    </section>
    <!-- /services -->
  </div>
</template>

<script>
export default {
  name: "Services2",
};
</script>

