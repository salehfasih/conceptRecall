<template>
  <div class="contactpage">
    <Header />

    <div class="banner about-page" id="ban">
      <div class="ani_banner">
        <img src="../assets/images/Value_icon.png" alt="" />
      </div>
      <div class="container">
        <div class="row">
          <div class="col-xs-1 col-sm-1 col-md-7 col-lg-7 col-xl-7">
            <div class="header-contain">
              <div class="heading_one about-head-bef">
                <h1 class="text-uppercase">Our Contact</h1>
              </div>
              <div class="para client-para">
                <p>
                  So we are here for you. If you need any assistance just let us know. We
                  will meet your level of expectations by providing our exceptional
                  services
                </p>
              </div>
            </div>
          </div>
          <div class="col-xs-1 col-sm-1 col-md-5 col-lg-5 col-xl-5">
            <div class="main-img About-before-none">
              <img src="../assets/images/Contact.png" img-fluid mx-auto />
            </div>
          </div>
        </div>
        <div class="ani-banner_2">
          <img src="../assets/images/banner-after.png" alt="" />
        </div>
      </div>
    </div>
    <!-- banner End -->

    <div class="contact">
      <div class="container">
        <div class="middle-contain">
          <div class="head-six round">
            <h6 class="fw-bold t-uppercase">Contact Us</h6>
          </div>
          <div class="head-two bord-bot contact-head">
            <h2 class="fw-bold text-uppercase mob-head">
              How might we desig demand for your business?
            </h2>
          </div>
        </div>

        <div class="main_form">
          <form>
            <div class="row">
              <div class="form-group col-md-6">
                <label for="inputState"></label>
                <select id="inputState" class="form-control multiple">
                  <option selected>Choose...</option>
                  <option>One</option>
                  <option>Two</option>
                  <option>Three</option>
                  <option>Four</option>
                  <option>Five</option>
                  <option>Six</option>
                  <option>Seven</option>
                </select>
              </div>
              <div class="form-group col-md-6">
                <label for="inputEmail4"></label>
                <input
                  type="email"
                  class="form-control"
                  id="inputEmail4"
                  placeholder="Company Name"
                />
              </div>
              <div class="form-group col-md-6">
                <label for="inputPassword4"></label>
                <input
                  type="text"
                  class="form-control"
                  id="inputPassword4"
                  placeholder="First Name"
                />
              </div>
              <div class="form-group col-md-6">
                <label for="inputEmail4"></label>
                <input
                  type="email"
                  class="form-control"
                  id="inputEmail4"
                  placeholder="Last Name"
                />
              </div>
              <div class="form-group col-md-6">
                <label for="inputPassword4"></label>
                <input
                  type="password"
                  class="form-control"
                  id="inputPassword4"
                  placeholder="Phone"
                />
              </div>
              <div class="form-group col-md-6">
                <label for="inputEmail4"></label>
                <input
                  type="email"
                  class="form-control"
                  id="inputEmail4"
                  placeholder="Email"
                />
              </div>
              <div class="form-group col-md-12">
                <textarea
                  class="form-control"
                  aria-label="With textarea"
                  placeholder="Comment"
                ></textarea>
              </div>
              <div class="form-group col-md-12 text-right form-btn">
                <button type="submit" class="btn btn-primary form_btn">Submit</button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>

    <div class="map">
      <div class="row">
        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
          <div class="foter-nav last contact-Last">
            <h5 class="fw-bold">Contact Us</h5>
            <div class="foter-Four">
              <div class="last-footer cont-form">
                <ul>
                  <li>
                    <div class="ft-img">
                      <img src="../assets/images/Phone.svg" alt="" />
                    </div>
                    <a href="#">
                      <h4>Phone:</h4>
                      <h3>+(765) 123 92345</h3>
                    </a>
                  </li>

                  <li>
                    <div class="ft-img">
                      <img src="../assets/images/Email.svg" alt="" />
                    </div>
                    <a href="#">
                      <h4>Email:</h4>
                      <h3>info@conceptrecall.com</h3>
                    </a>
                  </li>

                  <li>
                    <div class="ft-img">
                      <img src="../assets/images/Location.svg" alt="" />
                    </div>
                    <a href="https://goo.gl/maps/dJ9bYV77tBKdFSo5A"
                      ><h4>Location</h4>
                      <h3>
                        3rd Floor, 1/6C, Sarah-e-Faisal Rd, Block-6 Nursery Karachi,
                        Karachi City, Sindh, Pakistan
                      </h3></a
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-6 col-lg-6 col-xl-6">
          <div class="map-img">
            <img src="../assets/images/map.png" alt="" />
          </div>
        </div>
      </div>
    </div>

    <Footer />
  </div>
</template>

<script>
import Footer from "./Footer.vue";
import Header from "./Header.vue";
export default {
  name: "Contact",
  components: {
    Header,
    Footer,
  },
};
</script>
