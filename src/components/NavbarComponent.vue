<template>
<nav class="navbar navbar-expand-lg bg-body-light fixed-top mx-auto mt-2">
  <div class="container-fluid d-flex justify-content-space-between">
    <a class="navbar-brand" href="#"><img src="https://i.postimg.cc/3x9LXK3n/maxwill-1edit.png" alt=""></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
      <ul class="navbar-nav d-flex gap-4 me-0 mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#showcase">About Me</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#resume">Resume</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#skills">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#projects">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#testimonials">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#contact">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>
<script>
export default {
    
}
</script>
<style scoped>
  nav {
  width: 90vw;
  border-radius: 27px;
  background-color: #ffffffd0;
  }
  img {
    width: 9rem;
  }
  a{
    font-family: 'Ubuntu Mono', monospace;
    font-size: 1rem
  }
  a:hover {
    color: #ff0044;
    animation: pop 0.3s 2;
    padding: 0;
  }

  
</style>