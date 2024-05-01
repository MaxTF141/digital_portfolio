<template>
    <section id="resume" class="p-md-5 p-1 py-5">
        <h1>RESUME</h1>
        <div class="timeline">
            <div class="timeline-badge right">
                <div class="content px-2" data-aos="fade-left">
                    <h4 class="">KUILS RIVER TECHNICAL HIGH SCHOOL</h4>
                    <p class="p-lg-3 pb-1">I graduated from high school with a diploma.</p>
                    <h5 class="">2015 - 2019</h5>
                </div>
            </div>
            <div class="timeline-badge left" data-aos="fade-right">
                <div class="content px-2">
                    <h4 class="">DE JAGERS UITRUSTERS</h4>
                    <p class="p-lg-3 pb-1">De Jagers is a retail store. I worked there for about two years as a temporary worker since I finished high school.</p>
                    <h5 class="">2020 - 2022</h5>
                </div>
            </div>
        </div>
        <div class="timeline">
            <div class="timeline-badge right" data-aos="fade-left">
                <div class="content px-2">
                    <h4 class="">iCollege (Bellville Campus)</h4>
                    <p class="p-lg-3 pb-1">I attended this college after I took a gap year after school. I studied IT Tech Support NQF4 during that year.</p>
                    <h5 class="">Feb 2021 - Dec 2021</h5>
                </div>
            </div>
            <div class="timeline-badge left" data-aos="fade-right">
                <div class="content px-2">
                    <h4 class="">LIFE CHOICES ACADEMY </h4>
                    <p class="p-lg-3 pb-1">Attended Life Choices' six months coding course. It's been a great experience. I began to love coding more and more. And I have learnt a lot and It's just not coding. Including Life Skills, Personal Development and Work Ethics Training.I love how they implement everything that you'll need even after you done with the Course.</p>
                    <h5 class="">Sept 2022 - Mar 2023</h5>
                </div>
            </div>
            <div class="timeline-badge right" data-aos="fade-left">
                <div class="content px-2">
                    <h4 class="">Life Choices Studio</h4>
                    <p class="p-lg-3 pb-1">After finishing my six-month coding course, I began an internal internship. I went through a learning journey that consisted of UI/UX, Wordpress, PHP, and SEO.</p>
                    <h5 class="">Apr - Jul 2023</h5>
                </div>
            </div>
            <div class="timeline-badge left" data-aos="fade-right">
                <div class="content px-2">
                    <h4 class="">IMQS Software</h4>
                    <p class="p-lg-3 pb-1">I began my journey as an Intern software developer within IMQS, where I acquired proficiency in TypeScript, Go Lang, PostgreSQL, and Docker. Additionally, I gained hands-on experience with GitHub and contributed to projects managed through Jira boards.</p>
                    <h5 class="">Aug 2023 - Present</h5>
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
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#resume {
    overflow-x: hidden;
}
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