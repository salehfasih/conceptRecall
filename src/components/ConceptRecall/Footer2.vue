<template>
  <div>
    <footer>
      <div class="container">
        <div class="row">
          <div class="footer-logo">
            <a href="#">
              <img src="../../assets/images/Logo Consept.svg" />
            </a>
            <div class="soical-media">
              <ul>
                <li>
                  <a href="#"><i class="fab fa-facebook-f"></i></a>
                </li>
                <li>
                  <a href="#"><i class="fab fa-twitter"></i></a>
                </li>
                <li>
                  <a href="#"><i class="fab fa-linkedin-in"></i></a>
                </li>
              </ul>
            </div>
          </div>
          <div class="footer-link">
            <h3>Our Links</h3>
            <ul>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/"
                >
                  Home</router-link
                >
              </li>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/About"
                >
                  About Us</router-link
                >
              </li>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/Services"
                >
                  Services</router-link
                >
              </li>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/Projects"
                  >Our Projects</router-link
                >
              </li>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/Clients"
                  >Our Clients</router-link
                >
              </li>

              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/Contact"
                  >Contact Us</router-link
                >
              </li>
            </ul>
          </div>
          <div class="footer-service">
            <h3>Our Services</h3>
            <ul>
              <li><a href="#">Mobile Apps</a></li>
              <li><a href="#">Website Development</a></li>
              <!-- <li><a href="#">Web Designing</a></li> -->
              <li><a href="#">Logo Designing</a></li>
              <li><a href="#">Digital Marketing</a></li>
              <li><a href="#">Branding & Designing</a></li>
              
            </ul>
          </div>
          <!-- <div class="recent-work">
            <h3>Recent Works</h3>
            <ul>
              <li><a href="#">Unilayer</a></li>
              <li><a href="#">CodeTribe</a></li>
              <li><a href="#">Truck & Parts</a></li>
              <li><a href="#">Inclusion capital</a></li>
              <li><a href="#">Zunj Union Market</a></li>
              <li><a href="#">KLY Bourne Profile</a></li>
              <li><a href="#">Fantastic Foursome</a></li>
            </ul>
          </div> -->
          <div class="soical-links">
            <h3>Contact Us</h3>
            <div class="icon-box">
              <div class="icon">
                <i class="fas fa-phone-alt"></i>
              </div>
              <div class="soical-content">
                <h4>Phone:</h4>
                <a href="tel:+76512392345">+(765) 123 92345</a>
              </div>
            </div>
            <div class="icon-box">
              <div class="icon">
                <i class="fas fa-envelope"></i>
              </div>
              <div class="soical-content">
                <h4>Email:</h4>
                <a href="mailto:info@conceptrecall.com">info@conceptrecall.com</a>
              </div>
            </div>
            <div class="icon-box">
              <div class="icon">
                <i class="fas fa-map-marker-alt"></i>
              </div>
              <div class="soical-content">
                <h4>Location:</h4>
                <p>
                  <a href="https://goo.gl/maps/PBzaA5fq84fMPmfK8">3rd Floor, 1/6C, Sarah-e-Faisal Rd,Block-6 Nursery Karachi, Karachi
                  City, Sindh,Pakistan</a>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="copyrght">
          <p>Copyrights 2021 All Rights Reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer2",
};
</script>

