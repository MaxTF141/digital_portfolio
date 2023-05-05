<template>
    <section id="showcase">
        <div class="devices-img d-flex justify-content-center"> 
        <img src="https://i.postimg.cc/RZZvjtqk/Group-16-1-1.png" alt="">
        </div>
    </section>
    <section id="about" class="d-flex justify-content-center align-items-center flex-column p-4">
        <div class="about-me-text">
        <h1 class="text-center">My name is Maxwill. Nice to meet you.</h1>
        <p class="text-center paragraphs">I'm from Kuils River, Cape Town and I was born and grew up in Wesbank. Since I was a little kid I always loved creating things. I love working out, playing chess and Sudoku.</p>
        <p class="text-center paragraphs">I always loved playing around with computers. Love solving technical problems. It was always a goal of mine to build a career in the tech industry. I love coding and can't wait to create projects of my own.</p>
        </div>
        <div class="extra-info">
        <p class="lead"><span class="ps-lg-3">WHAT //</span> WEB DEVELOPER</p>
        <p class="lead"><span class="">WHERE //</span> CAPE TOWN, WESTERN CAPE</p>
        <p class="lead"><span class="ps-lg-4">WHY // </span>PASSION</p>
        </div>
    </section>

</template>
<script>
export default {
    
}
</script>
<style>
.devices-img img{
  width: 18rem;
}

#about {
  background-color: #FF0044;
}
.about-me-text {
  width: 50vw;
}
#about p {
  font-family: 'Ubuntu Mono', monospace;
  color: #d7d7d7;
  font-size: 18px;
}
.about-me-text h1 {
  font-family: 'Chivo Mono', monospace;
  color: #ffffff;
  font-size: 20px;
}

#about span {
  color: #ffffff;
}

</style>