<template>
    <section id="skills" class="p-5">
        <div class="container-fluid">
            <h1>Skills And Tools </h1>
            <h4>Below is the skills and tools I use to bring my ideas to life.</h4>
            <div class="row">
                <div class="col-12 d-flex justify-content-center">
                    <div class="skills">
                        <Icon icon="fontisto:mysql" class="icon" color="white" />
                        <p>MySql</p>
                    </div>
                    <div class="skills">
                        <Icon icon="bi:github" class="icon" color="white" />
                        <p>Github</p>
                    </div>
                    <div class="skills">
                        <Icon icon="icomoon-free:html-five" class="icon" color="white" />
                        <p>HTML5</p>
                    </div>
                    <div class="skills">
                        <Icon icon="akar-icons:javascript-fill" class="icon" color="white" />
                        <p>Javascript</p>
                    </div>
                    <div class="skills">
                        <Icon icon="uiw:css3" class="icon" color="white" />
                        <p>CSS3</p>
                    </div>
                    <div class="skills">
                        <Icon icon="fa6-brands:bootstrap" class="icon" color="white" />
                        <p>Bootstrap</p>
                    </div>
                    <div class="skills">
                        <Icon icon="fa-brands:node-js" class="icon" color="white" />
                        <p>Node.js</p>
                    </div>
                    <div class="skills">
                        <Icon icon="akar-icons:vue-fill" class="icon" color="white" />
                        <p>Vue.js</p>
                    </div>
                    <div class="skills">
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
#skills h1 {
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
</style>