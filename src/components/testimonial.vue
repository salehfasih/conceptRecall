<template>
    <div class="testinomal" style="padding: 6.5% 0 4% 0;">
            <div class="container">
                <div class="heading-two d-flex justify-content-between align-itens-center">
                    <div class="middle-contain">
                        <div class="head-six round">
                            <h6 class="fw-bold" style="color:#E55B35;font-family: Arial;  font-size: 18px;">Our
                                Testimonials</h6>
                        </div>
                        <div class="head-two bord-bot">
                            <h2 class="fw-bold" style="font-size: 62px;">What Client's Say</h2>
                        </div>
                        <div class="para">
                            <p style="padding: 0 38% 0% 0;">Lorem Ipsum is simply dummy text of the printing and
                                typesetting been the industry's standard dummy text ever since the an unknown printer.
                            </p>
                        </div>
                    </div>
                </div>

                <Slider />
            </div>
        </div>
        <!-- testinomal End -->
</template>


<script>

import Slider from './slider.vue';
export default {
    name:'testimonial',
    components:{
        Slider
    }
}
</script>