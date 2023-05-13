<template>
  <Navbar />
  <Home />
  <About />
  <Resume />
  <Skills />
  <Projects />
  <Testimonials />
  <Contact />
  <Footer />
</template>

<script>
import Navbar from '@/components/NavbarComponent.vue'
import Home from '@/components/HomeComponent.vue'
import About from '@/components/AboutComponent.vue'
import Resume from '@/components/ResumeComponent.vue'
import Skills from '@/components/SkillsComponent.vue'
import Testimonials from '@/components/TestimonialsComponent.vue'
import Projects from '@/components/ProjectsComponent.vue'
import Contact from '@/components/ContactComponent.vue'
import Footer from '@/components/FooterComponent.vue'

export default {
  components: {
    Navbar,
    Home,
    About,
    Resume,
    Skills,
    Testimonials,
    Projects,
    Contact,
    Footer
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Chivo+Mono:wght@100;200&family=Ubuntu+Mono&display=swap');
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
html {
  overflow-x: hidden;
}

.skills:hover, .icon:hover, .contact-icons:hover {
    animation: rotate-vertical 1.1s ease-out;
}

button:hover {
    animation: pop 0.3s 2;
}


@keyframes rotate-vertical {
  0% {
    transform: rotateY(0deg);
  }
  100% {
    transform: rotateY(360deg);
  }
}

@keyframes pop {
  0% {
    transform: scale(1, 1);
  }
  50% {
    transform: scale(1.1, 1.1);
  }
  100% {
    transform: scale(1, 1);
  }
}


</style>
