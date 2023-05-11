<template>
    <section id="resume" class="p-md-5 p-1 py-5">
        <h1>RESUME</h1>
        <div class="timeline">
            <div class="timeline-badge right">
                <div class="content px-2" data-aos="fade-left">
                    <h4 class="">KUILS RIVER TECHNICAL HIGH SCHOOL</h4>
                    <p class="">I graduated from high school with a diploma.</p>
                    <h5 class="">2015 - 2019</h5>
                </div>
            </div>
            <div class="timeline-badge left" data-aos="fade-right">
                <div class="content px-2">
                    <h4 class="">DE JAGERS UITRUSTERS</h4>
                    <p class="">De Jagers is a retail store. I worked there for about two years as a temporary worker since I finished high school.</p>
                    <h5 class="">2015 - 2019</h5>
                </div>
            </div>
        </div>
        <div class="timeline">
            <div class="timeline-badge right" data-aos="fade-left" data-aos-easing="ease-in-out">
                <div class="content px-2">
                    <h4 class="">iCollege (Bellville Campus)</h4>
                    <p class="">I attended this college after I took a gap year after school. I studied IT Tech Support NQF4 during that year.</p>
                    <h5 class="">2015 - 2019</h5>
                </div>
            </div>
            <div class="timeline-badge left" data-aos="fade-right">
                <div class="content px-2">
                    <h4 class="">LIFE CHOICES CODING </h4>
                    <p class="">So far it's been a great experience here at Life Choices. I began to love coding more and more. And I have learnt a lot and It's just not coding.I love how they implement everything that you'll need after you done with the Course</p>
                    <h5 class="">2015 - 2019</h5>
                </div>
            </div>
            <div class="timeline-badge right" data-aos="fade-left">
                <div class="content px-2">
                    <h4 class="">LIFE CHOICES CODING </h4>
                    <p class="">So far it's been a great experience here at Life Choices. I began to love coding more and more. And I have learnt a lot and It's just not coding.I love how they implement everything that you'll need after you done with the Course</p>
                    <h5 class="">2015 - 2019</h5>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.timeline {
    position: relative;
    max-width: 1200px;
    margin: 0 auto;
    overflow-x: hidden;
}
.timeline::after {
    content: '';
    position: absolute;
    width: 6px;
    background-color: #FF0044;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -3px;
}
.timeline-badge {
    padding: 10px 40px;
    position: relative;
    background-color: inherit;
    width: 50%;
}
.timeline-badge::after {
    content: '';
    position: absolute;
    width: 25px;
    height: 25px;
    right: -13px;
    background-color: #ffffff;
    border: 4px solid #FF0044;
    top: 15px;
    border-radius: 50%;
    z-index: 1;
}
.left {
    left: 0;
}
.right {
    left: 50%;
}
.left::before {
    content: " ";
    height: 0;
    position: absolute;
    top: 22px;
    width: 0;
    z-index: 1;
    right: 30px;
    border: medium solid #FF0044;
    border-width: 10px 0 10px 10px;
    border-color: transparent transparent transparent #FF0044;
}
.right::before {
    content: " ";
    height: 0;
    position: absolute;
    top: 22px;
    width: 0;
    z-index: 1;
    left: 30px;
    border: medium solid #FF0044;
    border-width: 10px 10px 10px 0;
    border-color: transparent #FF0044 transparent transparent;
}
.right::after {
    left: -12px;
}
.content {
    padding: 20px 30px;
    position: relative;
    border-radius: 20px;
    background-color: #F4E9EC;
}

#resume p {
  font-family: 'Ubuntu Mono', monospace;
  color: #000000;
  font-size: 18px;
}
h1 {
  font-family: 'Ubuntu Mono', monospace;
  color: #e0e0e0;
  font-size: 5em;
}
#resume h4 {
  font-family: 'Chivo Mono', monospace;
  color: #000000;
  font-size: 20px;
  font-weight: 700;
}
#resume h5 {
  font-family: 'Chivo Mono', monospace;
  color: #000000;
  font-size: 15px;
  text-align: right;
}

@media screen and (max-width: 768px) {
    h1{
        font-size: 3em;
        text-align: center;
    }
    .timeline::after {
        left: 38px;
    }

    .timeline-badge {
        width: 100%;
        padding-left: 70px;
        padding-right: 25px;
    }

    .left::after,
    .right::after {
        left: 25px;
    }

    .right {
        left: 0%;
    }
    .left::before {
        display: none;
    }
}
</style>