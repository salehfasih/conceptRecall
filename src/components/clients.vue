<template>
    
     <div style="padding: 7% 0 2% 0;">
     <div class="container">
        <div class="heading-two">
            <div class="middle-contain">
                <div class="head-six"><h6 class="fw-bold" style="color:#E55B35;font-family: Arial;  font-size: 18px;">Brands</h6></div>
                <div class="head-two"  ><h2 class="fw-bold" style="font-size: 62px;" >Clients</h2></div>
            </div>
            <!-- <div class="btn">
                <a href="#">All Services</a>
            </div> -->
        </div>

        <b-container class="client" >
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
  <sequential-entrance  delay="2000" fromLeft>
            <div class="item-1 d-flex justify-content-center align-items-center" data-aos="fade-up">
                <div class="slid-img" >
                <img src="../assets/images/first.png" alt="">
            </div>
          </div>
          </sequential-entrance>
          <sequential-entrance  delay="2000" fromLeft>
            <div class="item-1 d-flex justify-content-center align-items-center">
                <div class="slid-img">
                    <img src="../assets/images/second.png" alt="">
                </div>
            </div>
            </sequential-entrance>
            <sequential-entrance  delay="2000" fromLeft>
            <div class="item-1 d-flex justify-content-center align-items-center">
                <div class="slid-img">
                    <img src="../assets/images/Third.png" alt="">
                </div>
            </div>
             </sequential-entrance>
             <sequential-entrance  delay="2000" fromLeft>
            <div class="item-1 d-flex justify-content-center align-items-center">
                <div class="slid-img">
                    <img src="../assets/images/fourth.png" alt="">
                </div>
                
            </div>
             </sequential-entrance>
            <sequential-entrance  delay="2000" fromLeft>
            <div class="item-1 d-flex justify-content-center align-items-center">
                <div class="slid-img">
                    <img src="../assets/images/fourth.png" alt="">
                </div>
                
            </div>
             </sequential-entrance>
            </slick >
            </b-row>
        </b-container >
      
</div></div>

</template>


<script>

import Slick from 'vue-slick'

export default {
    name:'Clients',
    components: { Slick },

    data() {
        return {
            slickOptions: {
                slidesToShow: 4,
                 infinite: true,
                        accessibility: true,
                        adaptiveHeight: false,
                        // arrows: true,
                        // dots: true,
                        draggable: true,
                        edgeFriction: 0.30,
                        swipe: true
                // Any other options that can be got from plugin documentation
            },
        };
    },

    // All slick methods can be used too, example here
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

