<template>
  
  <b-container id="owl-three"  class="testimonial">
<b-row>
  
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
  @lazyLoadError="handleLazeLoadError">
 
 
                 <div class="item-2  b-col-sm-4 "
                        style=" background-color: #fff;  border: 1px solid #DCD8E3; border-radius: 25px; margin: 0 2%;">
                        <div class="test-slide">
                            <img src="../assets/images/test_1.png" alt="">
                        </div>
                        <div class="para slider-para">
                            <p    style="padding: 0 5% 0% 5%; margin-top:14%;">Lorem Ipsum is simply dummy text of the
                                printing typesetting industry been the industry's standard dummy text ever since the
                                when an unknown printer took is simply</p>
                        </div>
                        <div class="test-slid-head" style="padding: 0 5%;">
                            <h5>Joe Napolitano</h5>
                            <h6>Co-Founder LTD</h6>
                        </div>
                        <div class="star-img">
                            <img src="../assets/images/strat.png" alt="">
                        </div>
                    </div> 
                    <div class="item-2  b-col-sm-4"
                        style=" background-color: #fff;  border: 1px solid #DCD8E3; border-radius: 25px; margin: 0 2%;">
                        <div class="test-slide">
                            <img src="../assets/images/test_2.png" alt="">
                        </div>
                        <div class="para slider-para">
                            <p style="padding: 0 5% 0% 5%; margin-top:14%;">Lorem Ipsum is simply dummy text of the
                                printing typesetting industry been the industry's standard dummy text ever since the
                                when an unknown printer took is simply</p>
                        </div>
                        <div class="test-slid-head" style="padding: 0 5%;">
                            <h5>Joe Napolitano</h5>
                            <h6>Co-Founder LTD</h6>
                        </div>
                        <div class="star-img">
                            <img src="../assets/images/strat.png" alt="">
                        </div>
                    </div>
                    <div class="item-2 b-col-sm-4"
                        style=" background-color: #fff;  border: 1px solid #DCD8E3; border-radius: 25px; margin: 0 2%;">
                        <div class="test-slide">
                            <img src="../assets/images/test_3.png" alt="">
                        </div>
                        <div class="para slider-para">
                            <p style="padding: 0 5% 0% 5%; margin-top:14%;">Lorem Ipsum is simply dummy text of the
                                printing typesetting industry been the industry's standard dummy text ever since the
                                when an unknown printer took is simply</p>
                        </div>
                        <div class="test-slid-head" style="padding: 0 5%;">
                            <h5 style="font-family: Arial;">Joe Napolitano</h5>
                            <h6 style="font-family: Arial;">Co-Founder LTD</h6>
                        </div>
                        <div class="star-img">
                            <img src="../assets/images/strat.png" alt="">
                        </div>
                     </div>

                      <div class="item-2 "
                        style=" background-color: #fff;  border: 1px solid #DCD8E3; border-radius: 25px; margin: 0 2%;">
                        <div class="test-slide">
                            <img src="../assets/images/test_3.png" alt="">
                        </div>
                        <div class="para slider-para">
                            <p style="padding: 0 5% 0% 5%; margin-top:14%;">Lorem Ipsum is simply dummy text of the
                                printing typesetting industry been the industry's standard dummy text ever since the
                                when an unknown printer took is simply</p>
                        </div>
                        <div class="test-slid-head" style="padding: 0 5%;">
                            <h5 style="font-family: Arial;">Joe Napolitano</h5>
                            <h6 style="font-family: Arial;">Co-Founder LTD</h6>
                        </div>
                        <div class="star-img">
                            <img src="../assets/images/strat.png" alt="">
                        </div>
                     </div>
                
      

</slick>
</b-row>
</b-container>
</template>

<script>
// import Vue from 'vue'
import Slick from 'vue-slick';


export default {
    
    components: { Slick},
    mounted() {
    this.$anime(/* ... animate something ... */)
  },

    data() {
        return {
            slickOptions: {
                slidesToShow: 3,
                 infinite: true,
                        accessibility: true,
                        adaptiveHeight: false,
                        arrows: true,
                        dots: true,
                        draggable: true,
                        edgeFriction: 0.30,
                        swipe: true
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
}
</script>

