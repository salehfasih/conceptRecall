<template>
  <div>
    <!-- recent-project -->
    <section class="our-skills">
      <div class="container">
        <img class="square-shap" src="../../assets/images/square.png" />
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
            Our Skills
          </h2>
          <p data-aos="fade-left" data-aos-easing="linear" data-aos-duration="600">
            Lorem Ipsum is simply dummy text of the printing and typesetting been the
            industry's standard dummy text ever since the an unknown printer took a galley
            of type scrambled it has survived not only remaining essentially unchanged.
          </p>
        </div>
        <div class="row skill-builder">
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
              <div class="builder-img">
                <img src="../../assets/images/bootstarp.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/logo04.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/google.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/Vector.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/Group 1070.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/pngwing.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/Group 1069.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/node.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/reactr.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/Group 1067.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/Vector-2.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/php.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/logo04.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/Group 1071.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/Vector-1.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/w3school.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/Adobe illustrator.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/css3.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/ueza9hwy.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/Vector-3.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/Vector-4.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/Vector-5.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/Group 1.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/Group 2.png" />
              </div>
            </div>
            <div class="col">
              <div class="builder-img">
                <img src="../../assets/images/html.png" />
              </div>
              <div class="builder-img">
                <img src="../../assets/images/Group 1068.png" />
              </div>
            </div>
          </slick>
        </div>
      </div>
    </section>
    <!-- /recent-project -->
  </div>
</template>

<script>
import Slick from "vue-slick";

export default {
  name: "OurSkills2",
  components: { Slick },
  mounted() {
    this.$anime(/* ... animate something ... */);
  },

  data() {
    return {
      slickOptions: {
        slidesToShow: 8,
        infinite: true,
        accessibility: true,
        adaptiveHeight: false,
        arrows: false,
        draggable: true,
        edgeFriction: 0.3,
        swipe: true,
        responsive: [
          {
            breakpoint: 1120,
            settings: {
              slidesToShow: 8,
              slidesToScroll: 1,
            },
          },
          {
            breakpoint: 800,
            settings: {
              slidesToShow: 5,
              slidesToScroll: 2,
            },
          },
          {
            breakpoint: 480,
            settings: {
              slidesToShow: 3,
              slidesToScroll: 1,
            },
          },
        ],

        // Any other options that can be got from plugin documentation
      },
    };
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
