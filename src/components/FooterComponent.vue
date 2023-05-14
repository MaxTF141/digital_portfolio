<template>
    <section id="footer"  class="pt-md-5">
        <div class="row pt-md-3">
            <div class="col-md-6 col-12 d-flex flex-column align-items-center gap-4">
                <a href="#"><img src="https://i.postimg.cc/qqCFtr2j/maxwill-1-3-edit-removebg-preview-1.png" alt=""></a>
                <div class="contact-icons d-flex flex-row gap-2">
                    <a href="https://github.com/MaxTF141" target="blank"><Icon icon="mdi:github" color="#fff" /></a>
                    <a href="https://www.linkedin.com/in/maxwill-isaacs-88a1a2212/" target="blank"><Icon icon="bi:linkedin" color="#fff" /></a>
                </div>
            </div>
            <div class="col-md-6 col-12 d-flex flex-column align-items-center">
                <h4>Quick links</h4>
                <ul>
                    <li><a href="#about">ABOUT</a></li>
                    <li><a href="#resume">RESUME</a></li>
                    <li><a href="#skills">SKILLS</a></li>
                    <li><a href="#projects">PROJECTS</a></li>
                    <li><a href="#testimonials">TESTIMONIALS</a></li>
                    <li><a href="#contacts">CONTACT</a></li>
                </ul>
            </div>
        </div>
        <hr class="mx-auto">
        <div class="copyright p-3">
            <p class="text-center">2023 &copy; Copyright Maxwill Isaacs</p>
        </div>
    </section>
</template>
<script>

import { Icon } from '@iconify/vue';
export default {
   components: {
    Icon
   } 
}
</script>
<style scoped>
#footer {
    height: fit-content;
    background-color: #ff0044;
}
img {
    width: 20rem;
}
li {
    font-family: 'Ubuntu Mono', monospace;
    list-style: none;
}
a{
    text-decoration: none;
    color: #ffffff;
}
hr {
    width: 40%;
}
p{
    font-size: 1rem;
    color: #ffffff;
}
</style>