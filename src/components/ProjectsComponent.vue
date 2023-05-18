<template>
    <section id="projects" class="p-md-5 p-2 py-5">
        <div class="container-fluid">
            <h1>Projects I've Built</h1>
            <div class="projects mx-auto justify-content-center">
                <div class="overlay-img">
                    <img class="d-lg-flex d-block justify-content-end" src="../assets/booking.png" alt="">

                </div>
                <div class="project-content d-flex flex-column align-items-end" data-aos="fade-left">
                    <h4 class="text-end py-3">Booking Secure</h4>
                    <div class="summary">
                        <p>I designed and developed this booking website for my Capstone Project, which happens to be my first full-stack project. Through this project, I was able to enhance my design thinking and time management skills. It really helped me grow as a developer</p>
                    </div>
                    <div class="links d-flex gap-2 py-2 ">
                        <a href="https://github.com/MaxTF141/Capstone_Project.git" target="blank"><Icon icon="iconoir:github" class="icon" color="#f04" /></a>
                        <a href="https://booking-860f4.web.app/" target="blank"><Icon icon="mdi:link-variant" class="icon" color="#f04" /></a>
                    </div>
                </div>
            </div>
            <div class="projects mx-auto justify-content-center">
                <div class="overlay-img-right">
                    <img class="d-lg-flex d-block justify-content-start" src="../assets/Screenshot(3).png" alt="">

                </div>
                <div class="project-content-left d-flex flex-column align-items-start" data-aos="fade-right">
                    <h4 class="text-end py-3">JS Calculator</h4>
                    <div class="summary">
                        <p>This project was my initial foot in the door of Javascript, and while it was challenging, I gained valuable knowledge throughout its development. As a newcomer to programming, I found the language difficult to understand initially, but I persevered and was pleased with the end result of my efforts.</p>
                    </div>
                    <div class="links d-flex gap-2 py-2 ">
                        <a href="https://github.com/MaxTF141/JSCalculator" target="blank"><Icon icon="iconoir:github" class="icon" color="#f04" /></a>
                        <a href="https://maxwill-jscalculator.netlify.app/" target="blank"><Icon icon="mdi:link-variant" class="icon" color="#f04" /></a>
                    </div>
                </div>
            </div>
            <div class="projects mx-auto justify-content-center">
                <div class="overlay-img">
                    <img class="d-lg-flex d-block justify-content-end" src="../assets/Screenshot(4).png" alt="">

                </div>
                <div class="project-content d-flex flex-column align-items-end" data-aos="fade-left">
                    <h4 class="text-end py-3">Dead Man's Tales</h4>
                    <div class="summary">
                        <p>I really like this project because it was a teamwork project. I did the backend and API with Node.js, and my teammate did the frontend. This was my first teamwork project, and it really helped to work with someone and share ideas. I really enjoyed building the backend of the project, and it really showed where my strengths and weaknesses lie.</p>
                    </div>
                    <div class="links d-flex gap-2 py-2 ">
                        <a href="https://github.com/MaxTF141/NodeJS-EOMP.git" target="blank"><Icon icon="iconoir:github" class="icon" color="#f04" /></a>
                        <a href="https://dead-mans-tales.web.app/" target="blank"><Icon icon="mdi:link-variant" class="icon" color="#f04" /></a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import {Icon} from '@iconify/vue' 
export default {
    components: {
        Icon
    }
}
</script>
<style scoped>
#projects {
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

p{
    font-family: 'Ubuntu Mono', monospace;
    color: #353535;
    font-size: 20px;
    text-align: center;
}

.projects {
    display: grid;
    grid-template-columns: repeat(14, 1fr);
    width: 75vw;
    margin-top: 120px;
    margin-bottom: 120px;
}

.overlay-img {
    grid-column: 1 / 8;
    grid-row: 1 /2;
}
.overlay-img-right {
    grid-column: 8 / 15;
    grid-row: 1 /2;
}

.overlay-img, .overlay-img-right {
  position: relative;
  z-index: 0;
}

img {
    position: relative;
    z-index: 1;
    opacity: 0.4;
    box-shadow: 2px 2px 3px #ccc;
    width: 100%;
    height: 100%;
    filter: blur(2px);
}

img:hover {
    opacity: 1 !important;
    filter: blur(0px);
}

.overlay-img::before, .overlay-img-right::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0.9;
  background-color: black;
  z-index: 1;
  filter: blur(1px);
}

.summary {
    background-color: #F4E9EC;
    border-radius: 20px;
    box-shadow: 2px 2px 3px #ccc;
}
.project-content {
    grid-column: 7 / 15;
    position: relative;
    z-index: 2;
}
.project-content-left {
    grid-column: 1 / 9;
    position: relative;
    z-index: 2;
}

img, .project-content {
    grid-row: 1 / 2;
}
.img-right, .project-content-left {
    grid-row: 1 / 2;
}

.icon {
    font-size: 2rem;
}

@media screen and (max-width: 1456px) and (min-width: 1024px) {
    .project-content {
    grid-column: 6 / 15;
    }   
    .project-content-left {
    grid-column: 1 / 10;
    }
    img {
    grid-column: 1 / 9;
    }
}

@media screen and (max-width: 1024px) {
    .projects {
        width: 90vw;
        position: relative;
        display: block;
    }

    .projects::before {
        content: "";
        display: block;
        position: absolute;
        top: 0;
        left: 0;
        z-index: 0;
        width: 100%;
        height: 100%;
        background-color: #000000a8; 
    }

    .overlay-img, .overlay-img-right {
        display: block;
        width: auto;
        height: 100%;
        width: 100%;
        object-fit: cover;
        position: absolute;
        z-index: -1;
    }
    .overlay-img::before, .overlay-img-right::before {
    content: '';
    position: absolute;
    background-color: rgba(0, 0, 0, 0);
    z-index: -2;
    filter: blur(0px);
    }
    .project-content, .project-content-left {
        position: relative;
        z-index: 2;
    }
    .summary {
        background-color: #00000000;
        box-shadow: none;
        padding: 10px;
    }
    img {
        display: none;
    }
    h1{
        font-size: 3em;
        text-align: center;
    }
    h4{
        text-align: center;
        color: #ff0044;
        padding: 10px !important;
    }
    p {
        color: #ffff;
    }
    .icon {
        font-size: 3rem;
        padding: 10px !important;
    }
}

</style>