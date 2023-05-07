<template>
    <section id="testimonials" class="p-md-5 p-2 py-5">
        <div class="container-fluid">
            <!-- <h1>Testimonials</h1> -->
            <h4>What co-workers and lectures say about me.</h4>
            <div class="row">
                <div class="col-12">
                <div id="carouselExampleCaptions" class="carousel slide">
                        <div class="carousel-indicators">
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                        </div>
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <div class="grid-wrapper">
                                    <div class="test">
                                        <div class="testimonial">
                                            <Icon icon="ooui:quotes-ltr" class="icon" color="#F4E9EC" />
                                            <p class="p-1">Maxwill is a guy who becomes very passionate towards something when he becomes interested in it. He is very friendly and open to help anyone that has difficulty with any topic. He shows amazing creativity and problem-solving skills already. I recommend him to any company.</p>
                                            <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#F4E9EC" :rotate="2" />
                                        </div>
                                        <img class="testimonial-img" src="../assets/Brandon.png" alt="">
                                    </div>
                                </div>
                                <!-- <div class="test mx-auto d-flex flex-column justify-content-center align-items-center">
                                    <div class="testimonial">
                                        <Icon icon="ooui:quotes-ltr" class="icon" color="#F4E9EC" />
                                        <p class="p-1">Maxwill is a guy who becomes very passionate towards something when he becomes interested in it. He is very friendly and open to help anyone that has difficulty with any topic. He shows amazing creativity and problem-solving skills already. I recommend him to any company.</p>
                                        <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#F4E9EC" :rotate="2" />
                                    </div>
                                    <div class="test1">
                                        <img class="testimonial-img" src="../assets/Brandon.png" alt="">
                                    </div>
                                </div> -->
                            </div>
                            <div class="carousel-item">
                                <div class="test mx-auto d-flex flex-column justify-content-end align-items-center">
                                    <div class="testimonial">
                                        <Icon icon="ooui:quotes-ltr" class="icon" color="#F4E9EC" />
                                        <p class="p-1">Maxwill is a guy who becomes very passionate towards something when he becomes interested in it. He is very friendly and open to help anyone that has difficulty with any topic. He shows amazing creativity and problem-solving skills already. I recommend him to any company.</p>
                                        <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#F4E9EC" :rotate="2" />
                                    </div>
                                    <div class="test1">
                                        <img class="testimonial-img" src="../assets/Tim.png" alt="">
                                    </div>
                                </div>
                            </div>
                            <div class="carousel-item">
                                <div class="test mx-auto d-flex flex-column justify-content-end align-items-center">
                                    <div class="testimonial">
                                        <Icon icon="ooui:quotes-ltr" class="icon" color="#F4E9EC" />
                                        <p class="p-1">Maxwill is a very creative, goal-getter, and well-behaved student. He does enjoy working with his classmates and works well on his project. He has gained knowledge of web development, including Bootstrap 5. I am very delighted to see him build more awesome projects, and most importantly, companies will love to hire such a developer.</p>
                                        <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#F4E9EC" :rotate="2" />
                                    </div>
                                    <div class="test1">
                                        <img class="testimonial-img" src="../assets/Joel.png" alt="">
                                    </div>
                                </div>                            
                            </div>
                            <div class="carousel-item">
                                <div class="test mx-auto d-flex flex-column justify-content-end align-items-center">
                                    <div class="testimonial">
                                        <Icon icon="ooui:quotes-ltr" class="icon" color="#F4E9EC" />
                                        <p class="p-1">Maxwill is a hardworking, results orientated team player. He has a keen eye for detail and always does the utmost to achieve a goal. I respect and admire this approach to problem solving as he has shown it's useful for technical as well as everyday problems. He's an inexpensive asset to any company out there looking to hire!</p>
                                        <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#F4E9EC" :rotate="2" />
                                    </div>
                                    <div class="test1">
                                        <img class="testimonial-img" src="../assets/Deno.png" alt="">
                                    </div>
                                </div>                            
                            </div>
                            <div class="carousel-item">
                                <div class="test mx-auto d-flex flex-column justify-content-end align-items-center">
                                    <div class="testimonial">
                                        <Icon icon="ooui:quotes-ltr" class="icon" color="#F4E9EC" />
                                        <p class="p-1">Maxwill is an exceptionally hard worker and always making time to assist anyone who is in need. Also goes the extra-mile when doing anything that has to be done. He is also very confident in his capabilities and never fails to get the Job done.</p>
                                        <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#F4E9EC" :rotate="2" />
                                    </div>
                                    <div class="test1">
                                        <img class="testimonial-img" src="../assets/Reece.png" alt="">
                                    </div>
                                </div>                            
                            </div>
                            <div class="carousel-item">
                                <div class="test mx-auto d-flex flex-column justify-content-end align-items-center">
                                    <div class="testimonial">
                                        <Icon icon="ooui:quotes-ltr" class="icon" color="#F4E9EC" />
                                        <p class="p-1">Maxwill seems to be very passionate in web development because he puts in 100% in every project does. He is always willing to help and goes the extra mile for students who are struggling on their projects.</p>
                                        <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#F4E9EC" :rotate="2" />
                                    </div>
                                    <div class="test1">
                                        <img class="testimonial-img" src="../assets/Javier.png" alt="">
                                    </div>
                                </div>                            
                            </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>

import { Icon } from '@iconify/vue';

export default {
	components: {
		Icon
	},
}

</script>
<style scoped>
h1 {
  font-family: 'Ubuntu Mono', monospace;
  color: #e0e0e0;
  font-size: 5em;
}
h4 {
  font-family: 'Chivo Mono', monospace;
  color: #000000;
  font-size: 20px;
}
.test {
    height: 50vh;
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: repeat(6, 1fr);
}
.test {
    grid-row: 2 / 7;
}
img {
    /* width: 100%; */
    height: 100%;
    grid-row: 1 / 7;
    grid-column: 8 / 10;
}
.testimonial {
    position: relative;
    z-index: 2;
    grid-row: 3 / 6;
    grid-column: 2 / 9;
    height: fit-content;
    background-color: #ff0044;
}
/* .test {
    width: 80vw;
    height: 60vh;
    background-color: #ffffff;
    position: relative;
} 
.test1 {
    position: absolute;
    height: 75%;
    width: 100%;
    background-color: #F4E9EC;
}
.testimonial-img {
    position: absolute;
    height: 110%;
    bottom: 0;
    right: 0;
}
.testimonial {
    left: 10%;
    width: 70%;
    height: fit-content;
    z-index: 1;
    background-color: #ff0044;
} */
.icon {
    padding: 0px;
    font-size: 2rem; 
}

p {
    font-family: 'Ubuntu Mono', monospace;
    color: #ffff;
    font-size: 1rem;
    text-align: center;
}

.carousel-control-next-icon {
    background: url('https://api.iconify.design/material-symbols/arrow-forward-ios-rounded.svg?color=%23f04') no-repeat center center / contain;
}
.carousel-control-prev-icon {
    background: url('https://api.iconify.design/material-symbols/arrow-back-ios-rounded.svg?color=%23f04&width=100&height=100') no-repeat center center / contain;
}
@media screen and (max-width: 1034px) {
    .testimonial {
        grid-column: 2 / 10;
    }
    img {
        grid-column: 8 / 10;
    }
}
</style>