<template>

<header  >
        <div class="main-navbar" v-scroll='handleScroll'>
        <b-container class="latest">
            <b-row class="main-header d-flex justify-content-between">
                <b-col  cols="4"  class="logo">
                    <img src="../assets/images/main-Logo.png" alt="">
                </b-col>
                <b-col  cols="2"></b-col>
                <b-col   cols="6" class="navbar">
                    <ul>
                        <li class="d-inline-block active"><a href="/">Home</a></li>
                        <li class="d-inline-block"><a href="/About">About</a></li>
                        <li class="d-inline-block"><a href="/Services">Services </a></li>
                        <li class="d-inline-block"><a href="/projects">Our Projects</a></li>
                        <li class="d-inline-block"><a href="/Clients">Our Clients</a></li>
                      
                        <li class="d-inline-block active-2"><a href="/Contact">Contact Us</a></li>
                      
                    </ul>
                </b-col>
            </b-row>
        </b-container>
         <b-navbar  class="menubar
         " toggleable type="light" variant="">
    

    <b-navbar-toggle target="navbar-toggle-collapse">
      <template #default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="/"><li class="d-inline-block active"><a href="/">Home</a></li></b-nav-item>
        <b-nav-item href="/About"><li class="d-inline-block"><a href="/About">About</a></li></b-nav-item>
        <b-nav-item href="/Services"><li class="d-inline-block"><a href="/Services">Services </a></li></b-nav-item>
        <b-nav-item href="/projects"> <li class="d-inline-block"><a href="/projects">Our Projects</a></li></b-nav-item>
        <b-nav-item href="/projects"> <li class="d-inline-block"><a href="/Clients">Our Clients</a></li></b-nav-item>
        <b-nav-item href="/projects"> <li class="d-inline-block"><a href="/projects">Our Projects</a></li></b-nav-item>
       
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
    </div>
    <b-navbar  class="menubar
         " toggleable type="light" variant="">
    
 <b-navbar-brand href="#"> 
     <div class='logo'>
                    <img src="../assets/images/main-Logo.png" alt="">
                    </div>
                </b-navbar-brand>
    <b-navbar-toggle target="navbar-toggle-collapse">
      <template #default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="/"><li class="d-inline-block active"><a href="/">Home</a></li></b-nav-item>
        <b-nav-item href="/About"><li class="d-inline-block"><a href="/About">About</a></li></b-nav-item>
        <b-nav-item href="/Services"><li class="d-inline-block"><a href="/Services">Services </a></li></b-nav-item>
        <b-nav-item href="/projects"> <li class="d-inline-block"><a href="/projects">Our Projects</a></li></b-nav-item>
        <b-nav-item href="/projects"> <li class="d-inline-block"><a href="/Clients">Our Clients</a></li></b-nav-item>
        <b-nav-item href="/projects"> <li class="d-inline-block"><a href="/contact">Contact us </a></li></b-nav-item>
       
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
    </header>
<!-- header End -->

    
</template>

<script>

import $ from 'jquery';
export default {
  name: "Header",
  data() {
      return {
          
      }
  },
  mounted() {
      $(document).ready(function(){
    $(window).scroll(function(){
       if(this.scrollY > 20){
           $('.main-navbar').addClass("sticky");
       }
       else{
        $('.main-navbar').removeClass("sticky");
       }
    }); 
});
  },
  methods: {
  handleScroll: function () {
    alert("Dddd");
    console.log('hello world');
      if (window.scrollY > 50) {
        this.setAttribute(
          'style',
          'background-color:#f6edf0 !important;'
        )
      }
      return window.scrollY > 100
    }
    }}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->


