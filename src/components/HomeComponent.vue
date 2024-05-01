<template>
  <section id="home" class="d-flex justify-content-center align-items-center flex-column">
    <div class="profile m-3">
      <h1 class="text-center">hi! I'm a <developer class="d-lg-inline-block"></developer></h1>
      <h3 class="text-center">Pushing the boundaries of my potential.I also build stuff.</h3>
      <div class="profile-img d-flex justify-content-center">
        <img src="https://i.ibb.co/W5rZzjk/Max-Colour-Compressed.png" alt="">
      </div>
    </div>
  </section>
</template>
<script>
import developer from '@/components/AnimationComponent.vue'
export default {
    components: {
      developer
    }
}
</script>
<style scoped>
#home {
  background-color: white;
  height: 100vh;
  width: 100%;
  left: 0px;
  top: 0px;
  overflow-x: hidden;
}

img {
  width: 11rem;
}
h1{
  font-family: 'Chivo Mono', monospace;
  font-weight: 200;
}
h3 {
  font-family: 'Chivo Mono', monospace;
  font-weight: 100;
  color: #a7a7a7;

}
#home span {
  color: #FF0044;
}

/* @media screen and(1024px) {
  .profile{
    
  }
} */
</style>