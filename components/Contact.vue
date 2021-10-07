<template>
   <div class="page-section">
  <div class="container">
    <div class="row">
      <div class="col-lg-7 py-3 mb-5 mb-lg-0">
        <div class="img-place w-lg-75 wow zoomIn">
          <img src="~/assets/img/contact_us6.svg" alt="">
        </div>
      </div>
      <div class="col-lg-5 py-3">
        <h1 class="wow fadeInUp">Need a help? <br>
        Don't worry just contact us</h1>

        <form method="POST" class="mt-5">
          <div class="form-group wow fadeInUp">
            <div class="mt-4">
                <label class="btn btn-fab btn-primary fg-white"><span class="mai-logo-facebook"></span></label>
                <a  class="infoalign" href="https://www.facebook.com/vincera.sports">facebook.com/vincera.sports</a>
            </div>
            <!-- <label for="name" class="fw-medium fg-grey">Fullname</label>
            <input type="text" class="form-control" id="name"> -->
          </div>

          <div class="form-group wow fadeInUp">
            <!-- <label for="email" class="fw-medium fg-grey">Email</label>
            <input type="text" class="form-control" id="email"> -->
            <div class="mt-4">
                <label class="btn btn-fab btn-primary fg-white"><span class="mai-logo-instagram"></span></label>
                <a class="infoalign" href="https://www.instagram.com/vincera_sports">instagram.com/vincera_sports</a>
            </div>
          </div>

          <!-- <div class="form-group wow fadeInUp">
            
            <div class="mt-4">
                <label class="btn btn-fab btn-primary fg-white"><span class="mai-logo-instagram"></span></label>
                <a class="infoalign" href="https://www.instagram.com/stridersmiles/">instagram.com/stridersmiles</a>
            </div>
          </div> -->

          <!-- <div class="form-group wow fadeInUp">
            <div class="mt-4">
                <label class="btn btn-fab btn-primary fg-white"><span class="mai-logo-flickr"></span></label>
                <a class="infoalign" href="https://www.flickr.com/photos/stridersmiles/">flickr.com/stridersmiles</a>
            </div>
          </div> -->
          <div class="form-group wow fadeInUp">
            <!-- <label for="message" class="fw-medium fg-grey">Message</label>
            <textarea rows="6" class="form-control" id="message"></textarea> -->
            <div class="mt-4">
                <label class="btn btn-fab btn-primary fg-white"><span class="mai-mail"></span></label>
                <label class="infoalign">rajesh@vincera.in</label>
            </div>
          </div>
          <div class="form-group wow fadeInUp">
            <!-- <label for="message" class="fw-medium fg-grey">Message</label>
            <textarea rows="6" class="form-control" id="message"></textarea> -->
            <div class="mt-4">
                <label class="btn btn-fab btn-primary fg-white"><span class="mai-call"></span></label>
                <label class="infoalign">+91 95516 22575</label>
            </div>
          </div>

          <!-- <div class="form-group mt-4 wow fadeInUp">
            <button type="submit" class="btn btn-primary">Send Message</button>
          </div> -->
        </form>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
@import url('../assets/css/maicons.css');
@import url('../assets/css/mobster.css');
.infoalign{
    padding: 0 2vw;
    font-family: 'Trebuchet MS';
    font-weight: bolder;
    text-decoration: none;
    color: black;
}
.page-section .container{
  background-color: aliceblue !important;
}
.btn-primary{
  background: linear-gradient(to right, red, purple);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  color:transparent;
}
</style>