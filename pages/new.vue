<template>
<div class="main">
    <!-- <div class="infobar">
        <h5>Important notification</h5>
        <p>50% off for new customers</p>
    </div> -->
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
    <div>
        <Footer/>
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
@import url('../assets/css/maicons.css');
@import url('../assets/css/mobster.css');

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
/* .bg-image{
    background-image: url('../assets/img/pattern_1.svg');
    background-color: white;
} */

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
        /* display: inline; */
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