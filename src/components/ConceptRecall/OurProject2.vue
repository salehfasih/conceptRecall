<template>
    <div>
         <!-- recent-project -->
            <section class="projects">
                <div class="container">
                    <div class="title-style">
                        <span class="brand" data-aos="fade-down" data-aos-easing="linear"
                        data-aos-duration="600">Our Work</span>
                        <h2 class="brand-title" data-aos="fade-down" data-aos-easing="linear"
                        data-aos-duration="600">Recent Projects</h2>
                        <router-link  data-aos="fade-down"
                                    data-aos-easing="linear"
                            data-aos-duration="1500" to="/Projects">All  Projects</router-link>
                        <p data-aos="fade-left" data-aos-easing="linear"
                        data-aos-duration="600">The work will be done according to your instructions which will surely meet your level of satisfaction and expectations.</p>
             
                     </div> 
                    <div class="row">
                        <img class="recent-ball" src="" />
                        <div class="col-6">
                            <div class="project-card" data-aos="fade-right"
                                    data-aos-easing="linear"
                                    data-aos-duration="1000">
                                <div class="card-img">
                                    <img src="../../assets/images/portfolies.png" />
                                </div>
                                <div class="card-content">
                                    <h2>Mobile Application</h2>
                                    <p>Our dedicated team of web designers & developers makes your web according to your instructions and expectations. The layouts, coding and technicalities has never been a hurdle for us.</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="project-card" data-aos="fade-left"
                                    data-aos-easing="linear"
                                    data-aos-duration="1000">
                                <div class="card-img">
                                    <img src="../../assets/images/profilio.png" />
                                </div>
                                <div class="card-content">
                                    <h2>Website Designing</h2>
                                    <p>Our dedicated team of web designers & developers makes your web according to your instructions and expectations. The layouts, coding and technicalities has never been a hurdle for us.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <img class="half-ball" src="../../assets/images/ball.png" />
                        <div class="col-6">
                            <div class="project-card" data-aos="fade-right"
                                    data-aos-easing="linear"
                                    data-aos-duration="1000">
                                <div class="card-img">
                                    <img src="../../assets/images/logo-portfolioo.png" />
                                </div>
                                <div class="card-content">
                                    <h2>Logo Designing</h2>
                                    <p>Our dedicated team of web designers & developers makes your web according to your instructions and expectations. The layouts, coding and technicalities has never been a hurdle for us.</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 digital">
                            <div class="project-card" data-aos="fade-left"
                                    data-aos-easing="linear"
                                    data-aos-duration="1000">
                                <div class="card-img">
                                    <img src="../../assets/images/digital-market.png" />
                                </div>
                                <div class="card-content">
                                    <h2>Digital Marketing</h2>
                                    <p>Our dedicated team of web designers & developers makes your web according to your instructions and expectations. The layouts, coding and technicalities has never been a hurdle for us.</p>
                                </div>
                            </div>
                        </div>
                        <img class="cream-ball" src="../../assets/images/light--pink.png" />
                    </div>
                </div>
            </section>
            <!-- /recent-project -->
    </div>
</template>


<script>
export default {
    name:'OurProject2'
}
</script>