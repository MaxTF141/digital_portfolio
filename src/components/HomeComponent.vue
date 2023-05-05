<template>
      <section id="home" class="d-flex justify-content-center align-items-center flex-column">
    <div class="profile">
      <h1 class="text-center">hi! I'm a <span>Web Developer</span></h1>
      <h3>Pushing the boundaries of my potential.I also build stuff.</h3>
      <div class="profile-img d-flex justify-content-center">
        <img src="https://i.postimg.cc/VvyNdJTL/Group-18.png" alt="">
      </div>
    </div>
  </section>
</template>
<script>
export default {
    
}
</script>
<style>
#home {
  background-color: white;
  min-height: 100vh;
  width: 100%;
  /* position: absolute; */
  left: 0px;
  top: 0px;

}

.profile img {
  width: 8rem;
}
.profile h1{
  font-family: 'Chivo Mono', monospace;
  font-weight: 200;
}
.profile h3 {
  font-family: 'Chivo Mono', monospace;
  font-weight: 100;
  color: #a7a7a7;

}
#home span {
  color: #FF0044;
}

</style>