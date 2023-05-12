<template>
    <section id="contact" class="">
        <h1>Get in touch</h1>
        <div class="container-fluid">
            <div class="row">
                <div class="col-md-6 col-12 d-flex flex-column gap-4">
                    <h4>Feel free to contact me in any way with the provided information below.</h4>
                    <div class="icon-container d-flex align-items-center gap-4">
                        <Icon class="contact-icons" icon="ic:outline-alternate-email" color="#f04" /> 
                        <p class="mb-0">isaacsmaxwill22@gmail.com</p>               
                    </div>
                    <div class="icon-container d-flex align-items-center gap-4">
                        <Icon class="contact-icons" icon="ic:baseline-phone-android" color="#f04" /> 
                        <p class="mb-0">+27 67 274 6346</p>               
                    </div>
                    <div class="icon-container d-flex align-items-center gap-4">
                        <a href="https://www.linkedin.com/in/maxwill-isaacs-88a1a2212/" target="blank"><Icon class="contact-icons" icon="bi:linkedin" color="#f04" /></a> 
                        <p class="mb-0">My LinkedIn</p>
                    </div>
                    <div class="icon-container d-flex align-items-center gap-4">
                        <Icon class="contact-icons" icon="mdi:address-marker-outline" color="#f04" /> 
                        <p class="mb-0">Kuils River, Cape Town</p>               
                    </div>
                </div>
                <div class="col-md-6 col-12">
                    <div class="form p-4">          
                        <h4>Send me a message</h4>
                        <form action="https://formspree.io/f/xlevokwe" method="post">
                            <div class="row mb-4">
                                <div class="col-12">
                                    <div class="form-outline">
                                        <in
                                        
                                        put type="text" id="form3Example1" class="form-control" name="firstname"
                                            placeholder="First Name" required />
                                    </div>
                                </div>
                            </div>
                            <div class="form-outline mb-4">
                                <input type="email" id="form3Example3" class="form-control" name="email"
                                    placeholder="Email Address" required />
                            </div>
                            <div class="form-outline mb-4">
                                <textarea class="form-control" id="form4Example3" name="message" rows="4"
                                    placeholder="Message" required></textarea>
                            </div>
                            <button type="submit" class="btn btn-success btn-block d-block mx-auto">Contact Me</button>
                        </form>
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
    }
}
</script>
<style>
#contact {
    min-height: fit-content;
    position: relative;
    padding: 60px;
    padding-bottom: 80px
}
h1 {
  font-family: 'Ubuntu Mono', monospace;
  color: #e0e0e0;
  font-size: 5em;
}
h4 {
  font-family: 'Chivo Mono', monospace;
  color: #000000;
  font-size: 20px;
}
.form {
    background-color: #ffff;
    position: absolute; 
    box-shadow: 0px 0px 28px -14px rgba(0,0,0,0.5);
    -webkit-box-shadow: 0px 0px 28px -14px rgba(0,0,0,0.5);
    -moz-box-shadow: 0px 0px 28px -14px rgba(0,0,0,0.5);  
    bottom: -50px;
    right: 10%;
}
.btn {
    background-color: #ff0044 !important;
    border-color: #ff0044 !important;
    box-shadow: 0px 0px 28px -14px rgba(0,0,0,0.5) !important;
    -webkit-box-shadow: 0px 0px 28px -14px rgba(0,0,0,0.5);
    -moz-box-shadow: 0px 0px 28px -14px rgba(0,0,0,0.5);
}
.contact-icons {
    font-size: 2rem; 
}

@media screen and (max-width: 1024px) {
    .form {
        position: static;
    }
}
</style>