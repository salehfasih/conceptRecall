<template>
    <div>
  

        <test/>
        <clients />
        <Brand />
        <values />
        <project />
        <skillsTestimonial />
        <testimonial />
        <Footer />
    </div>
</template>


<script>
// import Header from './Header.vue';
import Footer  from './Footer.vue';
// import sliderbanner from './sliderbanner.vue';
import clients from './clients.vue';
import Brand from './Branding.vue';
import values from './values.vue';
import project from './Projects.vue'
import  skillsTestimonial from './skillsTestimonial.vue';
import  testimonial from './testimonial.vue';
import   test  from './test.vue';





export default {
    name:'Home',
    components:{
        
 Footer,clients,Brand,
 values,project,skillsTestimonial,testimonial,test

    }

}
</script>