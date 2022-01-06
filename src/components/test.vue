<template>

  <div class="home">
    <b-carousel
    v-show="3"
      class="banner"
      v-model="slide"
      controls
      indicators
      :no-touch="false"
      img-width="1024"
      img-height="500"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd">
       <Header />
      <!-- Text slides with image -->
      <b-carousel-slide caption="" img-blank img-alt="" >
           <template>
               
              <div class="ani_banner">
         <img src="../assets/images/Value_icon.png" alt="">
         </div>
        <div class="item">
        <div class="container">
        <div class="row">
        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
            <div class="header-contain">
                 <div class="heading_one"> <h1>Mobile Application</h1> </div>
                <div class="para para-border"><p>Our dedicated team of web designers and developers makes your website according to your instructions and expectations. The layouts, coding and technicalities has never been a hurdle for us.</p></div>
               <div class="email-field">
                   <input type="text" placeholder="Email">
                   <button class="border-0"> <a href="#">Submit</a></button>
               </div>
            </div>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
        <div class="main-img main-slider-img  position">
            <img src="../assets/images/main-banner.png" alt="" class="img-fluid mx-auto">
        </div>
        </div>
        </div>
        <div class="ani-banner_2">
            <img src="../assets/images/banner-after.png" alt="">
        </div>
        </div>
        </div>
       </template>
        </b-carousel-slide>

      <b-carousel-slide caption="" img-blank img-alt="">
       <template>
           <div class="ani-banner_2">
            <img src="../assets/images/banner-after.png" alt="">
        </div>

        <div class="item">
            <div class="container">
                <div class="row">
                <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                    <div class="header-contain">
                        <div class="heading_one"> <h1>Mobile Application</h1> </div>
                        <div class="para para-border"><p>Our dedicated team of web designers and developers makes your website according to your instructions and expectations. The layouts, coding and technicalities has never been a hurdle for us.</p></div>
                       <div class="email-field">
                           <input type="text" placeholder="Email">
                           <button class="border-0"> <a href="#">Submit</a></button>
                       </div>
                    </div>
                </div>
                <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                <div class="main-img main-slider-img">
                    <img src="../assets/images/secondSlider.png" class="img-fluid mx-auto">
                </div>
                </div>
                </div>
                <div class="ani-banner_2">
                    <img src="../assets/images/banner-after.png" alt="">
                </div>
                </div>
        
            </div>
       </template>
      </b-carousel-slide  >
      <!-- slide 3 -->
    <b-carousel-slide  caption="" img-blank img-alt="" >
        <template>
                <div class="ani-banner_2">
                    <img src="../assets/images/banner-after.png" alt="">
                </div>
                 <div class="item">
                    <div class="container">
                        <div class="row">
                        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                            <div class="header-contain">
                                <div class="heading_one"> <h1>Mobile Application</h1> </div>
                                <div class="para para-border"><p>Our dedicated team of web designers and developers makes your website according to your instructions and expectations. The layouts, coding and technicalities has never been a hurdle for us.</p></div>
                               <div class="email-field">
                                   <input type="text" placeholder="Email">
                                   <button class="border-0"> <a href="#">Submit</a></button>
                               </div>
                            </div>
                        </div>
                        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                        <div class="main-img main-slider-img  bg-transparent ">
                            <img src="../assets/images/Slider_three.png" alt="" class="img-fluid mx-auto">
                        </div>
                        </div></div></div></div>

        </template>
        
     </b-carousel-slide>
      
    </b-carousel>

       <!-- test sliding  -->

  </div>

  
</template>

<script>
import  Header from './Header.vue';
  export default {
      name:'test',
      components:{
          Header
      },
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart() {
        this.sliding = true
      },
      onSlideEnd() {
        this.sliding = false
      }
    }
  }
</script>