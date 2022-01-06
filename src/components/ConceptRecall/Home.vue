<template>
  <div>
    <Header />
    <div class="main-content">
      <!-- hero-section -->

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
        <section class="hero-section">
          <div class="container">
            <img class="dark-dot" src="../../assets/images/circle-shap.png" />
            <div class="row">
              <div class="col">
                <h1 data-aos-easing="linear" data-aos-duration="600">
                  Mobile Application
                </h1>
                <p data-aos-easing="linear" data-aos-duration="600">
                  Our dedicated team of web designers and developers makes your website
                  according to your instructions and expectations. The layouts, coding and
                  technicalities has never been a hurdle for us.
                </p>
                <div class="newletter">
                  <form action="/action_page.php">
                    <input type="email" id="email" name="email" placeholder="Email" />
                    <input type="submit" />
                  </form>
                </div>
                <img class="c-shap" src="../../assets/images/angle.png" />
              </div>
              <div class="col">
                <div class="hero-img">
                  <img src="../../assets/images/Ellipse 11.png" alt="" id="Ellipse" />
                  <img src="../../assets/images/Layer-62.gif" alt="" id="mobile-app" />
                  <img src="../../assets/images/Message.gif" alt="" id="Message" />
                  <img src="../../assets/images/Buttons.gif" alt="" id="Buttons" />
                  <img src="../../assets/images/Chart.gif" alt="" id="Chart" />
                  <img src="../../assets/images/Gif-lines.gif" alt="" id="Gif-lines" />
                  <img src="../../assets/images/Gif-lines.gif" alt="" id="Gif-lines2" />
                  <img src="../../assets/images/Ball.gif" alt="" id="Ball-gif" />
                  <img src="../../assets/images/Flower.gif" alt="" id="Flower" />
                  <img src="../../assets/images/Tree.gif" alt="" id="tree" />
                </div>
              </div>
            </div>
          </div>
        </section>

        <section class="hero-section">
          <div class="container">
            <img class="dark-dot" src="../../assets/images/circle-shap.png" />
            <div class="row">
              <div class="col">
                <h1>Website Development</h1>
                <p>
                  Our dedicated team of web designers and developers makes your website
                  according to your instructions and expectations. The layouts, coding and
                  technicalities has never been a hurdle for us.
                </p>
                <div class="newletter">
                  <form action="/action_page.php">
                    <input type="email" id="email" name="email" placeholder="Email" />
                    <input type="submit" />
                  </form>
                </div>
                <img class="c-shap" src="../../assets/images/angle.png" />
              </div>
              <div class="col">
                <div class="hero-img">
                  <img src="../../assets/images/Ellipse 11.png" alt="" id="Ellipse" />
                  <img src="../../assets/images/Illustration.gif" alt="" id="desktop" />
                  <img src="../../assets/images/Message.gif" alt="" id="Message2" />
                  <img src="../../assets/images/Asset.gif" alt="" id="Asset" />
                  <img src="../../assets/images/Flower.gif" alt="" id="Flower2" />
                </div>
              </div>
            </div>
          </div>
        </section>

        <section class="hero-section">
          <div class="container">
            <img class="dark-dot" src="../../assets/images/circle-shap.png" />
            <div class="row">
              <div class="col">
                <h1>Logo & Branding</h1>
                <p>
                  Our dedicated team of web designers and developers makes your website
                  according to your instructions and expectations. The layouts, coding and
                  technicalities has never been a hurdle for us.
                </p>
                <div class="newletter">
                  <form action="/action_page.php">
                    <input type="email" id="email" name="email" placeholder="Email" />
                    <input type="submit" />
                  </form>
                </div>
                <img class="c-shap" src="../../assets/images/angle.png" />
              </div>
              <div class="col">
                <div class="hero-img">
                  <img src="../../assets/images/1st.gif" alt="" id="logo-gif" />
                   <img src="../../assets/images/Layer-11.png" alt="" id="Flower2" />
                </div>
              </div>
            </div>
          </div>
        </section>

        <section class="hero-section">
          <div class="container">
            <img class="dark-dot" src="../../assets/images/circle-shap.png" />
            <div class="row">
              <div class="col">
                <h1>Digital Marketing</h1>
                <p>
                  Our dedicated team of web designers and developers makes your website
                  according to your instructions and expectations. The layouts, coding and
                  technicalities has never been a hurdle for us.
                </p>
                <div class="newletter">
                  <form action="/action_page.php">
                    <input type="email" id="email" name="email" placeholder="Email" />
                    <input type="submit" />
                  </form>
                </div>
                <img class="c-shap" src="../../assets/images/angle.png" />
              </div>
              <div class="col">
                <div class="hero-img">
                  <img src="../../assets/images/Ellipse 11.png" alt="" id="Ellipse" />
                  <img src="../../assets/images/Digital-Marketing.gif" alt="" id="desktop" />
                 
                </div>
              </div>
            </div>
          </div>
        </section>
      </slick>

      <!-- /hero-section -->
    </div>
    <Clients />
    <Services2 />
    <Values2 />
    <OurProject2 />
    <OurSkills2 />
    <OurTestimonials />
    <Footer2 />
  </div>
</template>

<script>
import Slick from "vue-slick";
import Header from "../ConceptRecall/Header.vue";
import Clients from "../ConceptRecall/Clients2.vue";
import Services2 from "../ConceptRecall/Services2.vue";
import Values2 from "../ConceptRecall/Values2.vue";
import OurProject2 from "../ConceptRecall/OurProject2.vue";
import OurSkills2 from "./OurSkills2.vue";
import OurTestimonials from "./OurTestimonials.vue";
import Footer2 from "./Footer2.vue";
export default {
  name: "Home",
  components: {
    Header,
    Clients,
    Services2,
    Values2,
    OurProject2,
    OurSkills2,
    OurTestimonials,
    Footer2,
    Slick,
  },
  data() {
    return {
      slickOptions: {
        slidesToShow: 1,
        infinite: true,
        accessibility: true,
        adaptiveHeight: false,
        arrows: false,
        fade: true,
        draggable: true,
        dots: true,
        swipe: true,
        autoplay: true,
        autoplaySpeed: 3000,
        responsive: [
          {
            breakpoint: 1120,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
            },
          },
          {
            breakpoint: 800,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
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

