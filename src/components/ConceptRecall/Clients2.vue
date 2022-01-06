<template>
  <div>
    <!-- client-logo -->
    <!-- client-logo -->
    <section class="client-logo">
      <div class="container">
        <div class="title-style" data-aos="fade-left">
          <span class="brand">Brands</span>
          <h2 class="brand-title">Clients</h2>
        </div>
        <div
          class="row clientitem"
          data-aos="zoom-in-right"
          data-aos-easing="linear"
          data-aos-duration="600"
        >
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
            <b-col class="client-porfilio-img">
              <img src="../../assets/images/logo6.png" />
            </b-col>
            <b-col class="client-porfilio-img">
              <img src="../../assets/images/ckient.png" />
            </b-col>
            <b-col class="client-porfilio-img">
              <img src="../../assets/images/client-logo.png" />
            </b-col>
            <b-col class="client-porfilio-img">
              <img src="../../assets/images/logo8.png" />
            </b-col>
            <b-col class="client-porfilio-img">
              <img src="../../assets/images/logo_US.png" />
            </b-col>
            <b-col class="client-porfilio-img">
              <img src="../../assets/images/Group 2171.png" />
            </b-col>
            <b-col class="client-porfilio-img">
              <img src="../../assets/images/Component 7 – 11.png" />
            </b-col>
          </slick>
          <!-- <div class="client-porfilio-img">
                            <img src="../../assets/images/logo6.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/ckient.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/client-logo.png" />
                        </div> -->
        </div>
        <img class="roll" src="../../assets/images/roll.png" />
        <img class="cream-ball" src="../../assets/images/light--pink.png" />
      </div>
    </section>
    <!-- /client-logo -->
  </div>
</template>

<script>
import Slick from "vue-slick";
export default {
  components: { Slick },
  data() {
    return {
      slickOptions: {
        slidesToShow: 4,
        infinite: true,
        accessibility: true,
        adaptiveHeight: false,
        arrows: true,
        prevArrow:
          '<button class="slide-arrow prev-arrow"><i class="fas fa-arrow-left"></i></button>',
        nextArrow:
          '<button class="slide-arrow next-arrow"><i class="fas fa-arrow-right"></i></button>',
        dots: true,
        autoplay: true,
        autoplaySpeed: 2000,
        pauseOnHover: true,
        draggable: true,
        edgeFriction: 0.3,
        swipe: true,
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
