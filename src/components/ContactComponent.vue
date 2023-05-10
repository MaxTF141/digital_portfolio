<template>
    <section id="contact" class="p-md-5 p-2 py-5">
        <h1>Get in touch with me</h1>
        <div class="container-fluid">
            <div class="row">
                <div class="col-3">
                    <div class="form p-4">          
                        <h4>Send me a message</h4>
                        <form action="https://formspree.io/f/xlevokwe" method="post">
                            <!-- 2 column grid layout with text inputs for the first and last names -->
                            <div class="row mb-4">
                                <div class="col-12">
                                    <div class="form-outline">
                                        <input type="text" id="form3Example1" class="form-control" name="firstname"
                                            placeholder="First Name" required />
                                    </div>
                                </div>
                            </div>
    
                            <!-- Email input -->
                            <div class="form-outline mb-4">
                                <input type="email" id="form3Example3" class="form-control" name="email"
                                    placeholder="Email Address" required />
                            </div>
                            <!-- Message input -->
                            <div class="form-outline mb-4">
                                <textarea class="form-control" id="form4Example3" name="message" rows="4"
                                    placeholder="Message" required></textarea>
                            </div>
    
                            <!-- Submit button -->
                            <button type="submit" class="btn btn-success btn-block d-block mx-auto">Contact Me</button>
                        </form>
                    </div>
                </div>
                <div class="col-6">

                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style>
#contact {
    min-height: 100vh;
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
    /* background-color: #ff0044; */
    /* border-radius: 20px; */
    box-shadow: -1px 1px 12px -1px rgba(0,0,0,0.44);
-webkit-box-shadow: -1px 1px 12px -6px rgba(0,0,0,0.44);
-moz-box-shadow: -1px 1px 12px -1px rgba(0,0,0,0.44);}
</style>