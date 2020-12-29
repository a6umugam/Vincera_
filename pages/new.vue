<template>
<div class="main">
    <div class="infobar">
        <h5>Important notification</h5>
        <p>50% off for new customers</p>
    </div>
    <Navbar/>
    <div class="container new-container bg-image">
        <div class="new-banner">
            <img src="~/assets/pic1.jpg"/>
        </div>
        
        <div class="new-only-text" style="margin-top:21px">
            <h2>Vision and Mission</h2>
            <p>As children get older, it can be a challenge for them to get adequate daily physical activity. So we believe in inculcating sports from early childhood of a kid. Vincera Sports will become a organization where the spirit of sport is sown as a seed within kids from the younger age, which will make them achieve great heights in the field of sports.</p>
            <h1>"Sit Less. Move More. Play Together."</h1>
        </div>

        <div class="new-image-text">
            <h2>Gallery</h2>
            <Gallery/>
        </div>

        <div class="new-only-text">
            <h2>Clients</h2>
            <Clients/>
        </div>
        <div class="new-only-text-nobg" style="padding: 50px 0px;">
        <!-- <div class="new-only-text-nobg bg-image"> -->
            <h2>Training Programs</h2>
            <Trainingprograms/>
        </div>
        <div class="new-only-text">
            <h2>Complimentary Trails</h2>
            <p>We provide free training sessions for 1-2 weeks (comprising 3 sessions) as complimentary trials. You can avail all the free sessions to become acquainted with the training routines, the nature of training and our training process. Based on the complimentary trials, you can continue your training with our group.</p>
        </div>
        <div class="new-only-text-nobg">
        <!-- <div class="new-only-text-nobg bg-image"> -->
            <h2>Training Exercises</h2>
            <Trainingexer/>
        </div>
        <div class="new-only-text">
            <h2>Marathon Trials</h2>
            <p>We train enthusiasts for half marathon and full marathon. We train in groups outdoors in natural surroundings, providing you the opportunity to connect with nature and to meet and associate with like-minded people.</p>
            <p>Marathon running is typically accompanied by a specific training program. Runners may use a program that calls for four to six workouts per week, but there are times when you can only run three days per week. Running only three days per week has several benefits, including preventing injuries and overtraining, along with providing extra time for strength training workouts or recreational sports. Even though your schedule limits your training to three days per week, you can still cross the finish line of your next marathon.</p>
        </div>
        <div class="new-only-text-nobg">
        <!-- <div class="new-only-text-nobg bg-image"> -->
            <h2>Training Methods</h2>
            <Trainingmethod/>
        </div>
        <div class="new-only-text">
            <h2>Beep Test</h2>
            <p>The beep test is a physical fitness test of your aerobic fitness. To significantly improve your beep test score, you need to do specific and general aerobic type training. Although the aerobic energy system is primarily being tested, as in most activities it is not the sole energy source, and the anaerobic system (or speed endurance / lactate tolerance) also plays a part in the beep test performance as the speed increases and effort is required to slow down and accelerate away from each turn.</p>
        </div>
        <div class="new-only-text-nobg">
        <!-- <div class="new-only-text-nobg bg-image"> -->
            <h2>Kids Training</h2>
            <Kidstraining/>
        </div>
        <div class="new-only-text">
            <h2>Fitness Program in your Resisdential Area</h2>
            <p>Vincera Sports comes at your doorstep. We conduct Fitness and wellness program for adults and kids. We give training for marathon, athletes, Basket ball and weight loss. We organize Sports day events and also offer Beach and Hill training.</p>
            <Residentareatraining/>
        </div>
        <div class="new-only-text-nobg">
        <!-- <div class="new-only-text-nobg bg-image"> -->
            <h2>Events Organized</h2>
            <!-- <h6>Kids Athletic  Meet</h6>
            <p>Our first  event  kids athletic meet  2019  was  successfully conducted  on  August 25th 2019  at Jawharlal  Nehru  Stadium  for kids  from  UKG TO  VII  STD. 2 5+  schools participated .  No of  students  participated  1200+  & FOTT  FALL of 2500+</p> -->
            <!-- <p>GAGNER SOCIAL  MARATHON 2020 (Run for  old age home &  Special children) Our second  event   gagner  social Marathon  2020  was  conducted  on  2 nd February,2020  at  Elliot’s Beach  Besant  Nagar.  This marathon  was conducted  to support  old  age  home  & Special children. We had more than 900 participants and  foot  fall  of 1800+</p> -->
            <Eventsorganized/>
        </div>
        <div>
            <Footer/>
        </div>
        <!-- <div class="page-section">
  <div class="container">
    <div class="row">
      <div class="col-lg-7 py-3 mb-5 mb-lg-0">
        <div class="img-place w-lg-75 wow zoomIn">
          <img src="~/assets/img/contact_us3.svg" alt="">
        </div>
      </div>
      <div class="col-lg-5 py-3">
        <h1 class="wow fadeInUp">Need a help? <br>
        Don't worry just contact us</h1>

        <form method="POST" class="mt-5">
          <div class="form-group wow fadeInUp">
            <label for="name" class="fw-medium fg-grey">Fullname</label>
            <input type="text" class="form-control" id="name">
          </div>

          <div class="form-group wow fadeInUp">
            <label for="email" class="fw-medium fg-grey">Email</label>
            <input type="text" class="form-control" id="email">
          </div>

          <div class="form-group wow fadeInUp">
            <label for="message" class="fw-medium fg-grey">Message</label>
            <textarea rows="6" class="form-control" id="message"></textarea>
          </div>

          <div class="form-group mt-4 wow fadeInUp">
            <button type="submit" class="btn btn-primary">Send Message</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</div> -->

<!-- <div class="page-footer-section bg-dark fg-white">
  <div class="container">
    <div class="row mb-5 py-3">
      <div class="col-sm-6 col-lg-2 py-3">
        <h5 class="mb-3">Pages</h5>
        <ul class="menu-link">
          <li><a href="#" class="">Features</a></li>
          <li><a href="#" class="">Customers</a></li>
          <li><a href="#" class="">Pricing</a></li>
          <li><a href="#" class="">GDPR</a></li>
        </ul>
      </div>
      <div class="col-sm-6 col-lg-2 py-3">
        <h5 class="mb-3">Company</h5>
        <ul class="menu-link">
          <li><a href="#" class="">About</a></li>
          <li><a href="#" class="">Team</a></li>
          <li><a href="#" class="">Leadership</a></li>
          <li><a href="#" class="">Careers</a></li>
          <li><a href="#" class="">HIRING!</a></li>
        </ul>
      </div>
      <div class="col-md-6 col-lg-4 py-3">
        <h5 class="mb-3">Contact</h5>
        <ul class="menu-link">
          <li><a href="#" class="">Contact Us</a></li>
          <li><a href="#" class="">Office Location</a></li>
          <li><a href="#" class="">hello@mobster.com</a></li>
          <li><a href="#" class="">support@macodeid.com</a></li>
          <li><a href="#" class="">+808 11233 900</a></li>
        </ul>
      </div>
      <div class="col-md-6 col-lg-4 py-3">
        <h5 class="mb-3">Subscribe</h5>
        <p>Get some offers, news, or update features of application</p>
        <form method="POST">
          <div class="input-group">
            <input type="text" class="form-control" placeholder="Your email..">
            <div class="input-group-append">
              <button type="submit" class="btn btn-primary"><span class="mai-send"></span></button>
            </div>
          </div>
        </form>

        <div class="mt-4">
          <a href="#" class="btn btn-fab btn-primary fg-white"><span class="mai-logo-facebook"></span></a>
          <a href="#" class="btn btn-fab btn-primary fg-white"><span class="mai-logo-twitter"></span></a>
          <a href="#" class="btn btn-fab btn-primary fg-white"><span class="mai-logo-instagram"></span></a>
          <a href="#" class="btn btn-fab btn-primary fg-white"><span class="mai-logo-google"></span></a>
        </div>
      </div>
    </div>
  </div>

  <hr>

  <div class="container">
    <div class="row">
      <div class="col-12 col-md-6 py-2">
        <img src="~/assets/favicon-light.png" alt="" width="40">
 
        <p class="d-inline-block ml-2">Copyright &copy; <a href="https://www.macodeid.com/" class="fg-white fw-medium">MACode ID</a>. All rights reserved</p>
      </div>
      <div class="col-12 col-md-6 py-2">
        <ul class="nav justify-content-end">
          <li class="nav-item"><a href="#" class="nav-link">Terms of Use</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Privacy Policy</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Cookie Policy</a></li>
        </ul>
      </div>
    </div>
  </div>
</div> -->

    </div>
</div>
  
</template>

<script>
import Clients from '~/components/Clients.vue'
import Gallery from '~/components/Gallery.vue'
import Navbar from '~/components/Navbar.vue'
import Trainingprograms from '~/components/Trainingprograms.vue'
import Trainingexer from '~/components/Trainingexer.vue'
import Trainingmethod from '~/components/Trainingmethod.vue'
import Kidstraining from '~/components/Kidstraining.vue'
import Residentareatraining from '~/components/Residentareatraining.vue'
import Eventsorganized from '~/components/Eventsorganized.vue'
import Contact from '~/components/Contact.vue'
import Footer from '~/components/Footer.vue'
export default {
  components: { Clients, Gallery, Navbar, Trainingexer, Trainingprograms, Trainingmethod, Kidstraining, Residentareatraining, Eventsorganized, Contact, Footer },

}
</script>

<style>
/* .column img, .trpg img{
    background-color: #ffcc00;
} */
.main{
    /* background-color: lightsteelblue; */
}

.input-group-prepend,
.input-group-append {
  display: flex;
}

.input-group-prepend .btn,
.input-group-append .btn {
  position: relative;
  z-index: 2;
}

.input-group-prepend .btn:focus,
.input-group-append .btn:focus {
  z-index: 3;
}

.input-group-prepend .btn+.btn,
.input-group-prepend .btn+.input-group-text,
.input-group-prepend .input-group-text+.input-group-text,
.input-group-prepend .input-group-text+.btn,
.input-group-append .btn+.btn,
.input-group-append .btn+.input-group-text,
.input-group-append .input-group-text+.input-group-text,
.input-group-append .input-group-text+.btn {
  margin-left: -1px;
}

.input-group-prepend {
  margin-right: -1px;
}

.input-group-append {
  margin-left: -1px;
}

.input-group-text {
  display: flex;
  align-items: center;
  padding: 0.375rem 0.75rem;
  margin-bottom: 0;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #495057;
  text-align: center;
  white-space: nowrap;
  background-color: #e9ecef;
  border: 1px solid #ced4da;
  border-radius: 0.25rem;
}

.input-group-text input[type="radio"],
.input-group-text input[type="checkbox"] {
  margin-top: 0;
}

.input-group-lg>.form-control:not(textarea),
.input-group-lg>.custom-select {
  height: calc(1.5em + 1rem + 2px);
}

.input-group-lg>.form-control,
.input-group-lg>.custom-select,
.input-group-lg>.input-group-prepend>.input-group-text,
.input-group-lg>.input-group-append>.input-group-text,
.input-group-lg>.input-group-prepend>.btn,
.input-group-lg>.input-group-append>.btn {
  padding: 0.5rem 1rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 0.3rem;
}

.input-group-sm>.form-control:not(textarea),
.input-group-sm>.custom-select {
  height: calc(1.5em + 0.5rem + 2px);
}

.input-group-sm>.form-control,
.input-group-sm>.custom-select,
.input-group-sm>.input-group-prepend>.input-group-text,
.input-group-sm>.input-group-append>.input-group-text,
.input-group-sm>.input-group-prepend>.btn,
.input-group-sm>.input-group-append>.btn {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 0.2rem;
}

.input-group-lg>.custom-select,
.input-group-sm>.custom-select {
  padding-right: 1.75rem;
}

.input-group>.input-group-prepend>.btn,
.input-group>.input-group-prepend>.input-group-text,
.input-group>.input-group-append:not(:last-child)>.btn,
.input-group>.input-group-append:not(:last-child)>.input-group-text,
.input-group>.input-group-append:last-child>.btn:not(:last-child):not(.dropdown-toggle),
.input-group>.input-group-append:last-child>.input-group-text:not(:last-child) {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0;
}

.input-group>.input-group-append>.btn,
.input-group>.input-group-append>.input-group-text,
.input-group>.input-group-prepend:not(:first-child)>.btn,
.input-group>.input-group-prepend:not(:first-child)>.input-group-text,
.input-group>.input-group-prepend:first-child>.btn:not(:first-child),
.input-group>.input-group-prepend:first-child>.input-group-text:not(:first-child) {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0;
}
.nav {
  display: flex;
  flex-wrap: wrap;
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
}
.justify-content-end {
  justify-content: flex-end !important;
}
.mb-3{
  margin-bottom: 1rem !important;
}
.mt-5,
.my-5 {
  margin-top: 3rem !important;
}
.mb-5,
.my-5 {
  margin-bottom: 3rem !important;
}
.py-2 {
  padding-top: 0.5rem !important;
}
.py-3 {
  padding-top: 1rem !important;
}
.mb-4 {
  margin-bottom: 1.5rem !important;
}
.ml-2,
.mx-2 {
  margin-left: 0.5rem !important;
}
.mt-4,
.my-4 {
  margin-top: 1.5rem !important;
}
.mb-lg-0,
.my-lg-0 {
  margin-bottom: 0 !important;
}
.fg-white {
  color: #fff !important;
}
.fw-medium {
  font-weight: 500 !important;
}
.fg-gray {
  color: #6B6872 !important;
}
@media (min-width: 992px) {
  .w-lg-75 {
    width: 75% !important;
  }
}
.menu-link {
  position: relative;
  padding-left: 0;
  list-style: none;
}

.menu-link li {
  display: block;
  margin: 10px 0;
}

.menu-link li a {
  padding-top: 6px;
  padding-bottom: 6px;
  color: #B2B4BF;
}

.menu-link li a:hover {
  /* color: #526bf5; */
  color:light;
  text-decoration: none;
}
.page-footer-section {
  position: relative;
  padding-top: 100px;
  padding-bottom: 20px;
  background-color: #F0EEF5;
  width: 100%;
  padding-left: 30px;
  padding-right: 30px;
}
.page-footer-section.bg-dark .caption {
  color: rgba(255, 255, 255, 0.6);
}

.page-footer-section.bg-dark hr {
  border-color: #4d4853;
}
.page-footer-section a,
.page-footer-section p {
  color: #B2B4BF;
}

.page-footer-section a:hover {
  /* color: #526bf5; */
  color: lightsteelblue;
  text-decoration: none;
}
.btn-fab {
  padding: 0;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  line-height: 45px;
  text-align: center;
  font-size: 16px;
}

.btn-fab.btn-sm {
  padding: 0;
  width: 30px;
  height: 30px;
  line-height: 30px;
  font-size: 12px;
}

.btn-fab.btn-lg {
  padding: 0;
  width: 60px;
  height: 60px;
  line-height: 60px;
  font-size: 21px;
}
.navbar-nav .nav-link {
  font-weight: 500;
}
.nav-link {
  display: block;
  padding: 0.5rem 1rem;
}

.nav-link:hover,
.nav-link:focus {
  text-decoration: none;
}

.nav-link.disabled {
  color: #6c757d;
  pointer-events: none;
  cursor: default;
}
.nav-tabs .nav-link {
  border: 1px solid transparent;
  border-top-left-radius: 0.25rem;
  border-top-right-radius: 0.25rem;
}

.nav-tabs .nav-link:hover,
.nav-tabs .nav-link:focus {
  border-color: #e9ecef #e9ecef #dee2e6;
}

.nav-tabs .nav-link.disabled {
  color: #6c757d;
  background-color: transparent;
  border-color: transparent;
}

.nav-tabs .nav-link.active,
.nav-tabs .nav-item.show .nav-link {
  color: #495057;
  background-color: #fff;
  border-color: #dee2e6 #dee2e6 #fff;
}

.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}

.nav-pills .nav-link {
  border-radius: 0.25rem;
}

.nav-pills .nav-link.active,
.nav-pills .show>.nav-link {
  color: #fff;
  /* background-color: #007bff; */
  background-color: lightsteelblue;
}
.navbar-nav .nav-link {
  padding-right: 0;
  padding-left: 0;
}
/* .col-md-6 {
    flex: 0 0 50%;
    max-width: 50%;
  } */
.col-12{
  position: relative;
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
}
.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:hover,
a.bg-dark:focus,
button.bg-dark:hover,
button.bg-dark:focus {
  background-color: #1d2124 !important;
}
.d-inline-block {
  display: inline-block !important;
}

.btn-primary {
  color: #ffffff;
  /* background-color: #3D58F3; */
  background-color: lightsteelblue !important;
  border-color: transparent !important;
}

.btn-primary:hover {
  color: #ffffff;
  /* background-color: #1737f1; */
  background-color: #3D58F3 !important;
  box-shadow: 0 4px 12px rgba(61, 88, 243, 0.3);
}

.btn-primary:focus {
  color: #ffffff;
  /* background-color: #1737f1; */
  background-color: lightsteelblue;
  box-shadow: none;
}
.img-place {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  width: 100%;
  height: 100%;
  text-align: center;
  overflow: hidden;
}

.img-place > img {
  width: 100%;
  height: 100%;
}

.img-place.w-auto > img {
  width: auto;
  max-width: 100%;
}

.img-place.h-auto > img {
  height: auto;
  max-height: 100%;
}

.img-place.custom-size > img {
  width: unset;
  height: unset;
}


@font-face {
  font-family: 'maicons';
  src:  url('../assets/fonts/maicons.eot?c9nlkl');
  src:  url('../assets/fonts/maicons.eot?c9nlkl#iefix') format('embedded-opentype'),
    url('../assets/fonts/maicons.ttf?c9nlkl') format('truetype'),
    url('../assets/fonts/maicons.woff?c9nlkl') format('woff'),
    url('../assets/fonts/maicons.svg?c9nlkl#maicons') format('svg');
  font-weight: normal;
  font-style: normal;
  font-display: block;
}

[class^="mai-"], [class*=" mai-"] {
  /* use !important to prevent issues with browser extensions that change fonts */
  font-family: 'maicons' !important;
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;

  /* Better Font Rendering =========== */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.mai-logo-facebook:before {
  content: "\ebe0";
}
.mai-logo-facebook-f:before {
  content: "\ebe1";
}
.mai-logo-twitter:before {
  content: "\ec4d";
}
.mai-logo-instagram:before {
  content: "\ec00";
}
.mai-logo-google:before {
  content: "\ebf2";
}
.mai-send:before {
  content: "\eb2d";
}
.new-only-text{
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    padding: 50px 100px;
    border-radius: 21px;
    /* background-color: #ffcc00; */
    background-color: lightsteelblue;
}
.new-only-text-nobg{
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    padding: 50px 100px;
}
.new-image-text{
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    /* padding: 100px 200px; */
    padding: 50px 0px;
}
h2, h6{
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-weight: bolder;
    /* border-bottom: 3px solid black; */
}
.bg-image{
    background-image: url('../assets/img/pattern_1.svg');
    background-color: white;
}

.new-only-text h1{
    text-align: center;
    /* background-color: peru; */
    background-color: steelblue;
    border-radius: 7px;
    padding: 8px;
    color: white;
    font-family: fantasy;
}

.new-container{
    display: flex;
    flex-flow: column;
    width: 100vw;
    justify-content: center;
    align-items: center;
}

.infobar{
    display: flex;
    width: 100%;
    /* background-color: peru; */
    /* background-color: royalblue; */
    /* color: white; */
    color: #000;
    justify-content: space-between;
    padding: 3px 30px 3px 30px;
    align-items: center;
}

.infobar p{
    margin-bottom: 0px;
}

.new-banner{
    /* margin-top: 20px; */
    padding-top: 20px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    /* border-radius: 21px; */
    max-height: 500px;
}
.new-banner img{
    /* width: inherit; */
    flex-shrink: 0;
    min-width: 80%;
    min-height: 100%;
    width: 100%;
}

@media only screen and (max-width: 800px) {
    .infobar{
        display: none;
    }
    .new-only-text{
    padding: 5px 50px;
    }
    .new-only-text-nobg{
        padding: 5px 5px;
    }
    .new-image-text{
        padding: 5px 0px;
    }
    .column{
        width:100%;
        padding: 7px 12px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

}
</style>