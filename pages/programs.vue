<template>
<div class="main">
    <!-- <div class="infobar">
        <h5>Important notification</h5>
        <p>50% off for new customers</p>
    </div> -->
    <Navbar/>
    <div class="container new-container bg-image">
        
        
       
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

    </div>
    <br>
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