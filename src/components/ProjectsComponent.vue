<template>
    <section id="projects" class="p-5">
        <div class="container-fluid">
            <h1>Projects I've Built</h1>
            <div class="projects mx-auto">
                <img class="d-flex justify-content-end" src="../assets/booking.png" alt="">
                <div class="project-content d-flex flex-column align-items-end">
                    <h4 class="text-end py-3">Booking Secure</h4>
                    <div class="summary">
                        <p>I designed and developed this booking website for my Capstone Project, which happens to be my first full-stack project. Through this project, I was able to enhance my design thinking and time management skills. It really helped me grow as a developer</p>
                    </div>
                    <div class="links d-flex gap-2 py-2 ">
                        <Icon icon="iconoir:github" class="icon" color="#f04" />
                        <Icon icon="mdi:link-variant" class="icon" color="#f04" />
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

p {
    font-family: 'Ubuntu Mono', monospace;
    color: #353535;
    font-size: 20px;
    text-align: center;
}

.projects {
    display: grid;
    grid-template-columns: repeat(14, 1fr);
    width: 75vw;
}

.summary {
    width: 100%;
    background-color: #F4E9EC;
    border-radius: 20px;
    box-shadow: 2px 2px 3px #ccc;
}
.project-content {
    grid-column: 7 / 14;
}

img {
    box-shadow: 2px 2px 3px #ccc;
    width: 40vw;
    grid-column: 1 / 8;
}

img, .project-content {
    grid-row: 1 / 2;
}

.icon {
    font-size: 2rem;
}


@media screen and (min-width: 1024px) {
    .project-content {
    grid-column: 7 / 15;
    }

}
</style>