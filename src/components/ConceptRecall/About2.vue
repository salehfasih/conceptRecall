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
              About Us
            </h1>
            <p data-aos="fade-left" data-aos-easing="linear" data-aos-duration="600">
              We Are a Team of makers, creatives, and strategic thinkers that help our
              partners design forward-thinking brands, business models, and experiences.
            </p>
            <div class="newletter">
              <img class="roll" src="../../assets/images/roll.png" />
            </div>
            <img class="c-shap" src="../../assets/images/angle.png" />
          </div>
          <div class="col">
            <div class="hero-img"  id="about-banner-image">
             <img src="../../assets/images/Ellipse 11.png" alt="" id="Ellipse" />
                  <img src="../../assets/images/Illustration.gif" alt="" id="desktop" />
                  <img src="../../assets/images/Message.gif" alt="" id="Message2" />
                  <img src="../../assets/images/Asset.gif" alt="" id="Asset" />
                  <img src="../../assets/images/Flower.gif" alt="" id="Flower2" />
              <img
                class="roll"
                src="../../assets/images/roll.png"
                data-aos="fade-down"
                data-aos-duration="800"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- /hero-section -->
    <Clients />
    <div class="client-text2">
      <h2>A Culture of Change</h2>
      <p>
        At Concept Recall, we bring life to the ideas of our clients by implementing
        state-of-the-art techniques to bring innovative solutions on board. We are here to
        help you revolutionize your business with digital marketing techniques and
        products from our digital realm to create your presence where most of your
        audience exist.
      </p>
    </div>
    <Values2 />
    <OurTestimonials />
    <Footer2 />
  </div>
</template>

<script>
import Header from "../ConceptRecall/Header.vue";
import Values2 from "./Values2.vue";
import Clients from "../ConceptRecall/Clients2.vue";
import OurTestimonials from "./OurTestimonials.vue";
import Footer2 from "./Footer2.vue";
export default {
  name: "About2",
  components: { Header, Values2, OurTestimonials, Footer2, Clients },
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
        draggable: true,
        edgeFriction: 0.3,
        swipe: true,
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

