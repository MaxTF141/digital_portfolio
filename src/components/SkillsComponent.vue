<template>
    <section id="skills" class="p-md-5 p-2 py-5"  data-aos="fade-up">
        <h1>Skills And Tools </h1>
        <h4>Below is the skills and tools I use to bring my ideas to life.</h4>
        <div class="container-fluid">
            <div class="row justify-content-center">
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="fontisto:mysql" class="icon" color="white"/>
                        <p>MySql</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="bi:github" class="icon" color="white" />
                        <p>Github</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="icomoon-free:html-five" class="icon" color="white" />
                        <p>HTML5</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="akar-icons:javascript-fill" class="icon" color="white" />
                        <p>Javascript</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="uiw:css3" class="icon" color="white" />
                        <p>CSS3</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="fa6-brands:bootstrap" class="icon" color="white" />
                        <p>Bootstrap</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="fa-brands:node-js" class="icon" color="white" />
                        <p>Node.js</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="akar-icons:vue-fill" class="icon" color="white" />
                        <p>Vue.js</p>
                    </div>
                </div>
                <div class="col-lg-1 col-4 mx-0 mx-lg-4 mx-xl-0 d-flex justify-content-center">
                    <div class="skills" data-aos="fade-up">
                        <Icon icon="mdi:vs-code" class="icon" color="white" />
                        <p>VS Code</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { Icon } from '@iconify/vue';
export default {
	components: {
		Icon
	},
}
</script>
<style scoped>
*,
*::after,
::before{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

#skills {
    background-color: #ff0044;
}
h1 {
  font-family: 'Ubuntu Mono', monospace;
  color: #e0e0e0;
  font-size: 5em;
}
i {
    padding: 20px;
    padding-bottom: 0px;
    font-size: 8em;
}
img {
    padding: 20px;
    padding-bottom: 0px;
    width: 10em;
}
p {
    font-family: 'Ubuntu Mono', monospace;
    color: #353535;
    font-size: 20px;
    text-align: center;
}
.icon {
    padding: 20px;
    padding-bottom: 0px;
    font-size: 8em; 
}
h4 {
  font-family: 'Chivo Mono', monospace;
  color: #000000;
  font-size: 20px;
}

@media screen and (max-width: 1024px) {
    h1{
        font-size: 3em;
        text-align: center;
    }
    h4{
        text-align: center;
    }
}
</style>