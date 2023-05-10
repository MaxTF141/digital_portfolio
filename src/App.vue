<template>
  <Navbar />
  <Home />
  <About />
  <Resume />
  <Skills />
  <Projects />
  <Testimonials />
  <Contact />
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

export default {
  components: {
    Navbar,
    Home,
    About,
    Resume,
    Skills,
    Testimonials,
    Projects,
    Contact
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Chivo+Mono:wght@100;200&family=Ubuntu+Mono&display=swap');
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
