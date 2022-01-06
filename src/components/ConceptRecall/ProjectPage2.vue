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
              Our Projects
            </h1>
            <p data-aos="fade-right" data-aos-easing="linear" data-aos-duration="600">
              Our diversified digital portfolio meet kind of your needs. The work will be
              done according to your instructions which will surely meet your level of
              satisfaction and expectations.
            </p>
            <div class="newletter">
              <img class="roll" src="../../assets/images/roll.png" />
            </div>
            <img class="c-shap" src="../../assets/images/angle.png" />
          </div>
          <div class="col">
            <div class="hero-img">
              <img src="../../assets/images/Project.gif" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Project -->
    <div class="project">
      <div class="container">
        <img class="u-shap" src="../../assets/images/u-angle.png" />
        <div class="title-style project-title">
          <span
            class="brand"
            data-aos="fade-left"
            data-aos-easing="linear"
            data-aos-duration="600"
            >Our Work</span
          >
          <h2
            class="brand-title"
            data-aos="fade-left"
            data-aos-easing="linear"
            data-aos-duration="600"
          >
            Our Portfolio
          </h2>
        </div>
        <div class="row">
          <ul class="our-porject">
            <li>
              <a class="tab active" id="open" href="#content">Mobile Application</a>
            </li>
            <li>
              <a class="tab" id="open2" href="#content2">Website Designing</a>
            </li>
            <li>
              <a class="tab" id="open3" href="#content3">Logo Designing</a>
            </li>
            <li>
              <a class="tab" id="open3" href="#content4">Digital Marketing</a>
            </li>
          </ul>
          <div class="tabcontent active" id="content">
            <div class="row">
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/Group26.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>

                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/Group26.png" alt="" />
                            <img src="../../assets/images/app2.png" alt="" />
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/app2.png" id="popup-image" />

                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>

                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/app2.png" alt="" />
                            <img src="../../assets/images/app2.png" alt="" />
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/portfolio3(3).png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>

                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                            <img src="../../assets/images/app2.png" alt="" />
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/app4.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/app4.png" alt="" />
                            <img src="../../assets/images/app2.png" alt="" />
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="tabcontent" id="content2">
            <div class="row">
              <!-- <div class="col-6">
                                    <div class="project-img">
                                        <img src="../../assets/images/Project.png" />
                                    </div>
                                </div> -->
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/project2.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/project2.png" alt="" />
                            <img src="../../assets/images/app2.png" alt="" />
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/project3.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/project3.png" alt="" />
                            <img src="../../assets/images/project2.png" alt="" />
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/project4.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/project4.png" alt="" />
                            <img src="../../assets/images/project2.png" alt="" />
                            <img src="../../assets/images/project3.png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/project5.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/project5.png" alt="" />
                            <img src="../../assets/images/project3.png" alt="" />
                            <img src="../../assets/images/project4.png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="tabcontent" id="content3">
            <div class="row">
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/logo1.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/logo1.png" alt="" />
                            <img src="../../assets/images/logo2.png" alt="" />
                            <img src="../../assets/images/logo3.png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/logo2.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/logo2.png" alt="" />
                            <img src="../../assets/images/logo1.png" alt="" />
                            <img src="../../assets/images/logo3.png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <!-- <div class="col-6">
                                        <div class="project-img">
                                            <img src="../../assets/images/project3.png" />
                                        </div>
                                    </div> -->
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/logo3.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/logo3.png" alt="" />
                            <img src="../../assets/images/app2.png" alt="" />
                            <img src="../../assets/images/portfolio3(3).png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/logo4.png" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/logo4.png" alt="" />
                            <img src="../../assets/images/logo3.png" alt="" />
                            <img src="../../assets/images/logo2.png" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="tabcontent" id="content4">
            <div class="row">
              <div class="col-6">
                <div class="project-img">
                  <img
                    src="../../assets/images/222.jpg"
                    id="popup-image"
                    data-description="Lorem Ipsum is simply dummy text of the printing and typesetting industry."
                    data-title="AMO ASSOCIATE"
                    data-url="https://amoassociate.com/"
                  />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup"></div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/dg2.jpg" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/dg2.jpg" alt="" />
                            <img src="../../assets/images/dg3.jpg" alt="" />
                            <img src="../../assets/images/888.jpg" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/dg3.jpg" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/dg3.jpg" alt="" />
                            <img src="../../assets/images/dg2.jpg" alt="" />
                            <img src="../../assets/images/888.jpg" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="project-img">
                  <img src="../../assets/images/888.jpg" id="popup-image" />
                  <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
                </div>
                <div class="overlay">
                  <div id="popup">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6" id="popp-slide-section">
                          <slick ref="slick" :options="slickOptions">
                            <img src="../../assets/images/888.jpg" alt="" />
                            <img src="../../assets/images/dg2.jpg" alt="" />
                            <img src="../../assets/images/888.jpg" alt="" />
                          </slick>
                          <img
                            src="../../assets/images/cancel.jpg"
                            id="popup-cancel-icon"
                          />
                        </div>
                        <div class="col-md-6">
                          <div class="title"><h1>AMO ASSOCIATE</h1></div>
                          <div class="descrition">
                            <p>
                              Our dedicated team of web designers and developers makes
                              your website according to your instructions and
                              expectations. The layouts, coding and technicalities has
                              never been a hurdle for us."
                            </p>
                          </div>
                          <div class="Read-more-btn">
                            <button id="visit-btn">
                              <a href="https://amoassociate.com/"> Visit Website</a>
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <img
          class="angle"
          src="../../assets/images/angle.png"
          id="popup-image"
          data-description="Lorem Ipsum is simply dummy text of the printing and typesetting industry."
          data-title="AMO ASSOCIATE"
          data-url="https://amoassociate.com/"
        />
        <img src="../../assets/images/cancel.jpg" alt="" id="cancle-btn" />
      </div>
      <div class="overlay">
        <div id="popup"></div>
      </div>
    </div>
    <!-- /Project -->

    <OurSkills2 />
    <OurTestimonials />
    <Footer />
  </div>
</template>

<script>
import Slick from "vue-slick";
import Header from "./Header.vue";
import Footer from "./Footer2.vue";
import OurSkills2 from "./OurSkills2.vue";
import OurTestimonials from "./OurTestimonials.vue";
import $ from "jquery";
export default {
  name: "ProjectPage",
  components: {
    Slick,
    Header,
    Footer,
    OurSkills2,
    OurTestimonials,
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
        // autoplay: true,
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
    $(document).ready(function () {
      $("#popup").hide();
      $(function () {
        $(".tab").click(function (e) {
          e.preventDefault();
          $(".tabcontent").hide();
          $(".tabcontent").removeClass("active");
          $(".tab").removeClass("active");
          var content = $(this).attr("href");
          $(this).addClass("active");
          $(content).addClass("active");
          //    jQuery('.tabcontent').addClass('active');

          $(content).show();
        });
      });

      $("body #popup-cancel-icon").on("click", function () {
        $(this).closest(".overlay").find("#popup").hide();
        $(".overlay").removeClass("intro");
      });

      $(".project-img").click(function () {
        $(".overlay").addClass("intro");
        $(this).closest(".col-6").find("#popup").show();
      });
    });
  },

  methods: {
    reInit() {
      // Helpful if you have to deal with v-for to update dynamic lists
      this.$nextTick(() => {
        this.$refs.slick.reSlick();
      });
    },
  },
};
</script>
