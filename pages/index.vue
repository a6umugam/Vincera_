<template>
<div class="main">
    <!-- <div class="infobar">
        <h5>Important notification</h5>
        <p>50% off for new customers</p>
    </div> -->
    <Navbar/>
    <div class="container new-container bg-image">
        <div class="new-banner">
            <img src="~/assets/baner.png"/>
        </div>
        
        <div class="new-only-text" style="margin-top:21px">
          <div class="subonlytext">
            <h2>Vision and Mission</h2>
            <div class='row'>
              <div class="col">
                <img src="~/assets/img/vision.svg" width="100%"/>
              </div>
              <div class="col">
                <p>As children get older, it can be a challenge for them to get adequate daily physical activity. So we believe in inculcating sports from early childhood of a kid. Vincera Sports will become a organization where the spirit of sport is sown as a seed within kids from the younger age, which will make them achieve great heights in the field of sports.</p>
              </div>
            </div>
            <h1>"Sit Less. Move More. Play Together."</h1> 
          </div>
        </div>

        <div class="new-image-text">
            <h2>Gallery</h2>
            <Gallery/>
        </div>

        <div class="new-only-text">
          <div class="subonlytext">
            <h2>Clients</h2>
            <Clients/>
          </div>
        </div>
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
.main{
  background-image: url('../assets/img/Rainbow-Vortex.svg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  color: aliceblue;
  /* position: fixed; 
  top: 0; 
  left: 0;  */

  /* Preserve aspet ratio */
  /* min-width: 100%; */
  /* min-height: 100%; */
}

.new-only-text{
    /* display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    padding: 50px 100px; */
    border-radius: 21px;
    /* background-color: #000000; */
    /* background-color: lightsteelblue; */
    color: rgb(255, 255, 255);
    /* max-width: 250px; */
    /* padding: 1rem; */
    /* position: relative; */
    background: linear-gradient(to right, red, purple);
    padding: 3px;
}
.subonlytext{
  background: rgb(0, 0, 0);
  /* color: rgb(0, 0, 0); */
  padding: 2rem;
  border-radius: 21px;
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
  padding: 50px 100px;
}
.new-only-text-nobg{
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
    padding: 50px 100px;
    /* background: linear-gradient(to right, red, purple); */
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
/* .bg-image{ */
    /* background-image: url('../assets/img/pattern_1.svg'); */
    /* background-image: url('../assets/img/Rainbow-Vortex.svg'); */
    /* background-color: white; */
/* } */

.new-only-text h1{
    text-align: center;
    background-color:crimson;
    /* background-color: steelblue; */
    border-radius: 7px;
    padding: 8px;
    color: white;
    font-family: fantasy;
    /* max-width: 80%; */
}

.new-container{
    /* display: flex; */
    flex-flow: column;
    width: 100%;
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
    .subonlytext{
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