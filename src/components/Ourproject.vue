<template>
    <div class="ourproject">
    
    <Header />
    
    
     <div class="banner about-page" id="ban">
    <div class="ani_banner">
        <img src="../assets/images/Value_icon.png" alt="">
     </div>
        <div class="container">
        <div class="row">
        <div class="col-xs-1 col-sm-1 col-md-7 col-lg-7 col-xl-7">
            <div class="header-contain">
                <div class="heading_one about-head-bef"> <h1 class="text-uppercase">Our Projects</h1> </div>
                <div class="para client-para"><p>Our diversified digital portfolio meet kind of your needs. The work will be done according to your instructions which will surely meet your level of satisfaction and expectations.</p></div>
            </div>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-5 col-lg-5 col-xl-5">
        <div class="main-img About-before-none project-img">
            <img src="../assets/images/Project.png" img-fluid mx-auto>
        </div>
        </div>
        </div>
        <div class="ani-banner_2">
            <img src="../assets/images/banner-after.png" alt="">
        </div>
        </div>
    </div>

 <!-- banner End -->

  <div class="project">
                                <div class="container">
                            <div class="heading-two">
                                <div class="middle-contain">
                                    <div class="head-six round project-round"><h6 class="fw-bold t-uppercase text-center">Our work</h6></div>
                                    <div class="head-two bord-bot bord-ceter pro-head"><h2 class="fw-bold text-uppercase text-center">Our Portfolio</h2></div>
                                </div>
                            </div>

                            <div class="main-btn d-flex justify-content-center align-items-center">
                                <button class="tablinks"  @click="openCity( 'MobileApplication')"> Mobile Application</button>
                                <button class="tablinks" @click="openCity( 'WebsiteDesigning')">Website Designing</button>
                                <button class="tablinks" @click="openCity( 'LogoDesigning')">Logo Designing</button>
                                <button class="tablinks" @click="openCity( 'DigitalMarketing')">Digital Marketing</button>
                            </div>

                        <div id="MobileApplication" class="tabcontent">
                            <div class="row">
                                <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                    <div class="mobile-app">
                                        <div class="temp d-flex justify-content-center align-items-center">
                                            <img src="../assets/images/template.png" alt="">
                                        </div>
                                    </div>
                                    <div class="mobile-app">
                                        <div class="temp d-flex justify-content-center align-items-center">
                                            <img src="../assets/images/template_3.png" alt="">
                                        </div>
                                    </div>
                                    </div>

                                    <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                        <div class="mobile-app">
                                            <div class="temp d-flex justify-content-center align-items-center">
                                                <img src="../assets/images/template_2.png" alt="">
                                            </div>
                                        </div>
                                        <div class="mobile-app">
                                            <div class="temp d-flex justify-content-center align-items-center">
                                                <img src="../assets/images/template_4.png" alt="">
                                            </div>
                                        </div>
                                        </div>
                                </div>
                                </div>    

                                <div id="WebsiteDesigning" class="tabcontent">
                                    <div class="row">
                                        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                            <div class="mobile-app">
                                                <div class="temp bord-none d-flex justify-content-center align-items-center">
                                                    <img src="../assets/images/Template_5.png" alt="">
                                                </div>
                                            </div>
                                            </div>
        
                                            <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                                <div class="mobile-app">
                                                    <div class="temp d-flex justify-content-center align-items-center">
                                                        <img src="../assets/images/template_6.png" alt="">
                                                    </div>
                                                </div>
                                                </div>
                                        </div>
                                        </div> 

                                        <div id="LogoDesigning" class="tabcontent">
                                            <div class="row">
                                                <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                                    <div class="mobile-app">
                                                        <div class="temp bord-none d-flex justify-content-center align-items-center">
                                                            <img src="../assets/images/template_7.png" alt="">
                                                        </div>
                                                    </div>
                                                    </div>
                
                                                    <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                                        <div class="mobile-app">
                                                            <div class="temp  d-flex justify-content-center align-items-center">
                                                                <img src="../assets/images/template_8.png" alt="">
                                                            </div>
                                                        </div>
                                                        </div>
                                                </div>
                                                </div> 

                                                <!-- <div id="DigitalMarketing" class="tabcontent">
                                                    <div class="row">
                                                        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                                            <div class="mobile-app">
                                                                <div class="temp d-flex justify-content-center align-items-center">
                                                                    <img src="./images/template.png" alt="">
                                                                </div>
                                                            </div>
                                                            </div>
                        
                                                            <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                                                <div class="mobile-app">
                                                                    <div class="temp d-flex justify-content-center align-items-center">
                                                                        <img src="./images/template_2.png" alt="">
                                                                    </div>
                                                                </div>
                                                                </div>
                                                        </div>
                                                        </div>  -->
                                
                                


                                <!-- <div class="row">
                                    <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                        <div id="MobileApplication" class="tabcontent">
                                        <div class="mobile-app">
                                            <div class="temp d-flex justify-content-center align-items-center">
                                                <img src="./images/template.png" alt="">
                                            </div>
                                        </div>
                            
                                        </div>
                                    </div>
                                    <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
                                        <div id="WebsiteDesigning" class="tabcontent">
                                        <div class="web-desig">
                                            <div class="temp d-flex justify-content-center align-items-center">
                                                <img src="./images/template_2.png" alt="">
                                            </div>
                                        </div>
                                        </div>
                                    </div>
                                    </div> -->
                                </div>
                            </div>
                            <!-- Project Template -->
                        
        <skillsTestimonial />
        <testimonial />
        <Footer />
 
    
          </div>
</template>


<script>

// import $ from "jquery";
import Header from './Header.vue';
import testimonial from './testimonial.vue';
import Footer from './Footer.vue';
import skillsTestimonial from './skillsTestimonial.vue';


export default {
    
    name: 'Ourproject',
    components:{
        Header,skillsTestimonial,testimonial,Footer
    },
    data() {
        return {
            
        }
    },


    methods: {
        
        openCity(cityName){

      var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        this.currentTarget.className += " active";
        }     
    },

}
</script>