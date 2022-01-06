<template>
  <div>
    <header>
      <b-container>
        <b-row>
          <div class="site-logo">
            <a :href="result">
              <img src="../../assets/images/Logo Consept.svg" />
            </a>
          </div>

          <div class="main-navbar">
            <ul class="navbar-menu">
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
                  to="/about"
                >
                  About Us</router-link
                >
              </li>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/services"
                >
                  Services</router-link
                >
              </li>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/projects"
                  >Our Projects</router-link
                >
              </li>
              <li>
                <router-link
                  class="rainbow-text animated"
                  data-splitting
                  class-active="active"
                  to="/clients"
                  >Our Clients</router-link
                >
              </li>
              <router-link
                class="rainbow-text animated"
                data-splitting
                class-active="active"
                to="/contact"
              >
                <li class="btn">
                  <a href="" class="rainbow-text animated" data-splitting>Contact Us</a>
                </li></router-link
              >
            </ul>
          </div>
          <div id="nav-icon2">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
          </div>
        </b-row>
      </b-container>
    </header>
  </div>
</template>

<script>
import $ from "jquery";
export default {
  name: "Header",

  data() {
    return {
      result: window.location.protocol + "//" + window.location.host,
    };
  },

  mounted() {
    $(document).ready(function () {
      $("#nav-icon2").click(function () {
        $(".main-navbar").toggleClass("open-menu");
        $(this).toggleClass("open");
        $(".main-navbar").toggle();
      });
    });
  },

  methods: {
    myFunction() {
      alert("hello world");
    },
  },
};
</script>
