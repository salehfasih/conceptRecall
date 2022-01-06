<template>
  <div>
    <section class="testimonial">
      <div class="container">
        <img class="shap" src="../../assets/images/angle.png" />
        <div class="title-style">
          <span
            class="brand"
            data-aos="fade-down"
            data-aos-easing="linear"
            data-aos-duration="600"
            >About Us</span
          >
          <h2
            class="brand-title"
            data-aos="fade-down"
            data-aos-easing="linear"
            data-aos-duration="600"
          >
            Our TESTIMONIAL
          </h2>
          <p data-aos="fade-left" data-aos-easing="linear" data-aos-duration="600">
            Lorem Ipsum is simply dummy text of the printing and typesetting been the
            industry's standard dummy text ever since the an unknown printer.
          </p>
        </div>
        <div class="row testimonialslides">
          <slick
            ref="slick"
            :options="slickOptions"
            @afterChange="handleAfterChange"
            @beforeChange="handleBeforeChange"
            @breakpoint="handleBreakpoint"
            @destroy="handleDestroy"
            @edge="handleEdge"
            @init="handleInit"
            @reInit="handleReInit"
            @setPosition="handleSetPosition"
            @swipe="handleSwipe"
            @lazyLoaded="handleLazyLoaded"
            @lazyLoadError="handleLazeLoadError"
          >
            <div class="col">
              <div
                class="slide"
                data-aos="zoom-out-down"
                data-aos-easing="ease-out-cubic"
                data-aos-duration="1000"
              >
                <div class="item-img">
                  <img src="../../assets/images/indignant.png" />
                  <p>
                    Lorem Ipsum is simply dummy text of the printing typesetting industry
                    been the industry's standard dummy text ever since the when an unknown
                    printer took is simply.
                  </p>
                  <div class="review-section">
                    <h3>Joe Napolitano</h3>
                    <span>Co-Founder LTD</span>
                    <ul>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                class="slide"
                data-aos="zoom-out-down"
                data-aos-easing="ease-out-cubic"
                data-aos-duration="1000"
              >
                <div class="item-img">
                  <img src="../../assets/images/capture.png" />
                  <p>
                    Lorem Ipsum is simply dummy text of the printing typesetting industry
                    been the industry's standard dummy text ever since the when an unknown
                    printer took is simply.
                  </p>
                  <div class="review-section">
                    <h3>Joe Napolitano</h3>
                    <span>Co-Founder LTD</span>
                    <ul>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                class="slide"
                data-aos="zoom-out-down"
                data-aos-easing="ease-out-cubic"
                data-aos-duration="1000"
              >
                <div class="item-img">
                  <img src="../../assets/images/portrait.png" />
                  <p>
                    Lorem Ipsum is simply dummy text of the printing typesetting industry
                    been the industry's standard dummy text ever since the when an unknown
                    printer took is simply.
                  </p>
                  <div class="review-section">
                    <h3>Joe Napolitano</h3>
                    <span>Co-Founder LTD</span>
                    <ul>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                class="slide"
                data-aos="zoom-out-down"
                data-aos-easing="ease-out-cubic"
                data-aos-duration="1000"
              >
                <div class="item-img">
                  <img src="../../assets/images/indignant.png" />
                  <p>
                    Lorem Ipsum is simply dummy text of the printing typesetting industry
                    been the industry's standard dummy text ever since the when an unknown
                    printer took is simply.
                  </p>
                  <div class="review-section">
                    <h3>Joe Napolitano</h3>
                    <span>Co-Founder LTD</span>
                    <ul>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                class="slide"
                data-aos="zoom-out-down"
                data-aos-easing="ease-out-cubic"
                data-aos-duration="1000"
              >
                <div class="item-img">
                  <img src="../../assets/images/capture.png" />
                  <p>
                    Lorem Ipsum is simply dummy text of the printing typesetting industry
                    been the industry's standard dummy text ever since the when an unknown
                    printer took is simply.
                  </p>
                  <div class="review-section">
                    <h3>Joe Napolitano</h3>
                    <span>Co-Founder LTD</span>
                    <ul>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                class="slide"
                data-aos="zoom-out-down"
                data-aos-easing="ease-out-cubic"
                data-aos-duration="1000"
              >
                <div class="item-img">
                  <img src="../../assets/images/portrait.png" />
                  <p>
                    Lorem Ipsum is simply dummy text of the printing typesetting industry
                    been the industry's standard dummy text ever since the when an unknown
                    printer took is simply.
                  </p>
                  <div class="review-section">
                    <h3>Joe Napolitano</h3>
                    <span>Co-Founder LTD</span>
                    <ul>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                      <li><i class="fas fa-star"></i></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </slick>
        </div>
        <img class="u-shap" src="../../assets/images/u-angle.png" />
      </div>
    </section>

    <!-- /testimonial -->
  </div>
</template>

<script>
import Slick from "vue-slick";
export default {
  components: { Slick },
  data() {
    return {
      slickOptions: {
        slidesToShow: 3,
        infinite: true,
        accessibility: true,
        adaptiveHeight: false,
        arrows: true,
        prevArrow:
          '<button class="slide-arrow prev-arrow"><i class="fas fa-arrow-left"></i></button>',
        nextArrow:
          '<button class="slide-arrow next-arrow"><i class="fas fa-arrow-right"></i></button>',
        draggable: true,
        edgeFriction: 0.3,
        swipe: true,
        autoplay: true,
        centerMode: true,
        autoplaySpeed: 4000,
        responsive: [
          {
            breakpoint: 1120,
            settings: {
              slidesToShow: 3,
              slidesToScroll: 1,
            },
          },
          {
            breakpoint: 800,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
            },
          },
          {
            breakpoint: 480,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
            },
          },
        ],

        // Any other options that can be got from plugin documentation
      },

      config: {
        num: [4, 3],
        rps: 0.1,
        radius: [5, 40],
        life: [1.5, 3],
        v: [2, 3],
        tha: [20, -40],
        alpha: [0.6, 0],
        scale: [0.1, 0.4],
        position: "all",
        cross: "dead",
        polygon: 34,
      },
    };
  },

  mounted() {
    this.$anime(/* ... animate something ... */);
  },

  methods: {
    // next() {
    //     this.$refs.slick.next();
    // },

    // prev() {
    //     this.$refs.slick.prev();
    // },

    reInit() {
      // Helpful if you have to deal with v-for to update dynamic lists
      this.$nextTick(() => {
        this.$refs.slick.reSlick();
      });
    },
  },
};
</script>

