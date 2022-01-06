<template>
    <div  class="clients">
        <Header />

 <div class="banner about-page"  id="ban">
    <div class="ani_banner">
        <img src="../assets/images/Value_icon.png" alt="">
    </div>
    <div class="container">
        <div class="row">
        <div class="col-xs-1 col-sm-1 col-md-7 col-lg-7 col-xl-7">
            <div class="header-contain">
                <div class="heading_one about-head-bef"> <h1 class="text-uppercase">Our Clients</h1> </div>
                <div class="para client-para"><p>We believe our clients are the key assets of our company. They are the primary stakeholders which provides potential to move further crossing all the obstacles.</p></div>
            </div>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-5 col-lg-5 col-xl-5">
        <div class="main-img About-before-none">
            <img src="../assets/images/LAPTOP-LEFT.png" img-fluid mx-auto>
        </div>
        </div>
        </div>
        <div class="ani-banner_2">
            <img src="../assets/images/banner-after.png" alt="">
        </div>
        </div>
    </div>
 <!-- banner End -->

<div class="Client">
     <div class="container">
        <div class="heading-two">
            <div class="middle-contain">
                <div class="head-six round project-round client-p"><h6 class="fw-bold t-uppercase text-center" >Our work</h6></div>
                  <div class="head-two bord-bot bord-ceter"><h2 class="fw-bold text-uppercase text-center">Our Portfolio</h2></div>
                  <div class="para clent"><p style="padding: 0 19% 0 19%;" class="text-center">We have a strong and large clientele who has firm belief in us and we exist because of their support. Some of them are:</p></div>
            </div>
        </div>

        <div class="anter-logo">
            <div class="row">
                <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                 <div class="logo-img">
                    <img src="../assets/images/first.png" alt="">
                 </div>
                </div>

                <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/second.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/Third.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/fourth.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/Fivth_logo.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/Sixth.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/true.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/Evth.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/Nine.png" alt="">
                    </div>
                   </div>

                   <div class="col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3">
                    <div class="logo-img">
                       <img src="../assets/images/last_img.png" alt="">
                    </div>
                   </div>
            </div>
        </div>
     </div>
 </div>
<!-- Client Logo End -->




 <testimonial />
<Footer />


    </div>
</template>



<script>
import Header from './Header.vue';
import testimonial from './testimonial.vue';
import Footer from './Footer.vue';
export default {
    name:'Clientspage',
    components:{
        Header,testimonial,Footer

    }
}
</script>