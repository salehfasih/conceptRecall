<template>
     <div>
     
<Header />

<div class="banner about-page"  id="ban">
    <div class="ani_banner">
        <img src="../assets/images/Value_icon.png" alt="">
    </div>
    <div class="container">
        <div class="row">
        <div class="col-xs-1 col-sm-1 col-md-7 col-lg-7 col-xl-7">
            <div class="header-contain">
                <div class="heading_one about-head-bef"> <h1 class="text-uppercase">About Us</h1> </div>
                <div class="para"><p>We Are a Team of makers, creatives, and strategic thinkers that help our partners design forward-thinking brands, business models, and experiences.</p></div>
            </div>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-5 col-lg-5 col-xl-5">
        <div class="main-img About-before-none ipad-img ">
            <img src="../assets/images/About-main.png">
        </div>
        </div>
        </div>
        <div class="ani-banner_2 about-anni">
            <img src="../assets/images/banner-after.png" alt="">
        </div>
        <div class="ani-banner_3">
            <img src="../assets/images/lenth.png" alt="">
        </div>
        <div class="ani-banner_3 ani-4">
            <img src="../assets/images/lenth.png" alt="">
        </div>
        </div>
    </div>
     
<!-- banner End -->
    <!-- client-logo -->
            <section class="client-logo">
                <div class="container">
                    <img class="u-shap" src="../../assets/images/u-angle.png" />
                    <div class="title-style">
                        <span class="brand">Brands</span>
                        <h2 class="brand-title">Clients</h2>
                    </div>
                  <div class="row clientitem">
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/logo8.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/logo6.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/ckient.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/client-logo.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/logo8.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/logo6.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/ckient.png" />
                        </div>
                        <div class="client-porfilio-img">
                            <img src="../../assets/images/client-logo.png" />
                        </div>
                  </div>

                  <div class="client-text">
                      <h2>A Culture of Change</h2>
                      <p>At Concept Recall, we bring life to the ideas of our clients by implementing state-of-the-art techniques to bring innovative solutions on board. We are here to help you revolutionize your business with digital marketing techniques and products from our digital realm to create your presence where most of your audience exist.</p>
                  </div>
                </div>

            </section>
            <!-- /client-logo -->
           
     <value />
     <testimonial />
    </div>
    

</template>




<script>
import Header from './Header.vue';
// import Client from './clients.vue';
import  value from './values.vue';
import testimonial from './testimonial.vue';
import Footer  from './Footer.vue'

export default {
    name:'About2',
    components:{
    Header,value,testimonial,Footer
        
    }
    

 
}
</script>