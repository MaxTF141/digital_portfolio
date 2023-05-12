<template>
    <section id="testimonials" class="p-md-5 p-2 py-5">
        <div class="container-fluid">
            <h1>Testimonials</h1>
            <h4>What co-workers and lectures say about me.</h4>
            <div class="row">
                <div class="col-12">
                    <div id="carouselExampleCaptions" class="carousel slide" data-aos="zoom-in-up">
                        <div class="carousel-indicators m-3">
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4" aria-label="Slide 5"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="5" aria-label="Slide 6"></button>
                        </div>
                        <div class="carousel-inner">
                            <div v-for="testimon in carouselActive" :key="testimon.id" class="carousel-item " :class="testimon.class">
                                <div class="grid-wrapper">
                                    <div class="test">
                                        <div class="testimonial">
                                            <Icon icon="ooui:quotes-ltr" class="icon" color="#ff0044" />
                                            <p class="p-1">{{ testimon.testimonial }}</p>
                                            <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#ff0044" :rotate="2" />
                                        </div>
                                        <img class="testimonial-img" :src="testimon.image" alt="">
                                    </div>
                                </div>
                            </div>
                            <div v-for="testimon in carousel" :key="testimon.id" class="carousel-item">
                                <div class="grid-wrapper">
                                    <div class="test">
                                        <div class="testimonial">
                                            <Icon icon="ooui:quotes-ltr" class="icon" color="#ff0044" />
                                            <p class="p-1">{{ testimon.testimonial }}</p>
                                            <Icon icon="ooui:quotes-ltr" class="icon d-flex ms-auto" color="#ff0044" :rotate="2" />
                                        </div>
                                        <img class="testimonial-img" :src="testimon.image" alt="">
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
    data() {
        return {
            carouselActive: [
                {
                    id: 1,
                    name: "Brandon",
                    testimonial: "Maxwill is very committed in his work. He loves learning. An incredible problem solver. His very discipline worker. Always willing to assist those in need. I enjoyed having Maxwill as a fellow developer.",
                    title: "Colleague",
                    image: "https://i.postimg.cc/nLgnhNtS/Brandon.png",
                    class: 'active'
                }
            ],
            carousel: [
                {
                    id: 2,
                    name: "Timmothy",
                    testimonial: "Maxwill is a guy who becomes very passionate towards something when he becomes interested in it. He is very friendly and open to help anyone that has difficulty with any topic. He shows amazing creativity and problem-solving skills already. I recommend him to any company.",
                    title: "Colleague",
                    image: "https://i.postimg.cc/zGfNSqzP/Tim.png"
                },
                {
                    id: 3,
                    name: "Joel",
                    testimonial: "Maxwill is a very creative, goal-getter, and well-behaved student. He does enjoy working with his classmates and works well on his project. He has gained knowledge of web development, including Bootstrap 5. I am very delighted to see him build more awesome projects, and most importantly, companies will love to hire such a developer.",
                    title: "Lecturer",
                    image: "https://i.postimg.cc/N05gYBZr/Joel.png"
                },
                {
                    id: 4,
                    name: "Deno",
                    testimonial: "Maxwill is a hardworking, results orientated team player. He has a keen eye for detail and always does the utmost to achieve a goal. I respect and admire this approach to problem solving as he has shown it's useful for technical as well as everyday problems. He's an inexpensive asset to any company out there looking to hire!",
                    title: "Colleague",
                    image: "https://i.postimg.cc/d1Cwknss/Deno.png"
                },
                {
                    id: 5,
                    name: "Reece",
                    testimonial: "Maxwill is an exceptionally hard worker and always making time to assist anyone who is in need. Also goes the extra-mile when doing anything that has to be done. He is also very confident in his capabilities and never fails to get the Job done.",
                    title: "Colleague",
                    image: "https://i.postimg.cc/8cVDhWch/Reece.png"
                },
                {
                    id: 6,
                    name: "Javier",
                    testimonial: "Maxwill seems to be very passionate in web development because he puts in 100% in every project does. He is always willing to help and goes the extra mile for students who are struggling on their projects.",
                    title: "Colleague",
                    image: "https://i.postimg.cc/C5H0J1n9/Javier.png"
                },
 
            ]
        }
    }
}

</script>
<style scoped>
#testimonials {
    background-color: #FF0044;
    overflow-x: hidden;
}
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
    height: 100%;
    grid-row: 1 / 7;
    grid-column: 9 / 11;
}
.testimonial {
    position: relative;
    z-index: 2;
    grid-row: 3 / 6;
    grid-column: 2 / 10;
    height: fit-content;
    background-color: #F4E9EC;
}

.icon {
    padding: 0px;
    font-size: 2rem; 
    font-family: #ff0044;
}

p {
    font-family: 'Ubuntu Mono', monospace;
    color: #ff0044;
    font-size: 1rem;
    text-align: center;
}

.carousel-control-next-icon {
    background: url('https://api.iconify.design/material-symbols/arrow-forward-ios-rounded.svg?color=white') no-repeat center center / contain;
}
.carousel-control-prev-icon {
    background: url('https://api.iconify.design/material-symbols/arrow-back-ios-rounded.svg?color=white&width=100&height=100') no-repeat center center / contain;
}
@media screen and (max-width: 1034px) {
    .testimonial {
        grid-column: 2 / 10;
    }
    img {
        grid-column: 8 / 10;
    }
    h1 {
        font-family: 'Ubuntu Mono', monospace;
        color: #e0e0e0;
        font-size: 3em;
    }
    h4 {
        font-family: 'Chivo Mono', monospace;
        color: #000000;
        font-size: 20px;
    }
}
</style>