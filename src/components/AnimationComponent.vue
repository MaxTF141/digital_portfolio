<template>
    <div class="name">
      <div class="letter">S</div>
      <div class="letter">O</div>
      <div class="letter">F</div>
      <div class="letter">T</div>
      <div class="letter">W</div>
      <div class="letter">A</div>
      <div class="letter">R</div>
      <div class="letter pe-4">E</div>
      <div class="letter">D</div>
      <div class="letter">E</div>
      <div class="letter">V</div>
      <div class="letter">E</div>
      <div class="letter">L</div>
      <div class="letter">O</div>
      <div class="letter">P</div>
      <div class="letter">E</div>
      <div class="letter">R</div>
    </div>
  </template>
  
  <script>
  import anime from 'animejs';
  
  export default {
    mounted() {
      anime({
        targets: '.letter',
        opacity: 1,
        scale: 1,
        easing: 'easeInBounce',
        delay: (el, index) => index * 80,
        direction: 'alternate',
        loop: true
      });
    }
  };
  </script>
  
  <style>
  @import url('https://fonts.googleapis.com/css2?family=Chivo+Mono:wght@100;200&family=Ubuntu+Mono&display=swap');

  .name {
    display: flex;
    margin: auto;
    padding: 0 1rem 1rem;
    position: relative;
    width: fit-content;
  }

  .letter {
    display: inline-block;
    opacity: 0;
    transform: scale(0.9);
    color: #ff0044;
    font-family: 'Chivo Mono', monospace;
    font-weight: 200;
  }
  </style>