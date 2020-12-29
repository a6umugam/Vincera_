<template>
  <div @resize="processBullets()" @load="processBullets()">
        <Navbar/>
            <div class='main'>
            <div class='fill'>
                <img src="@/assets/pic1.jpg" alt="" contain height="auto" width="auto" class='center'/>
            </div>
            <div class="vision">
                <label class="display-4" >Vision and Mission</label>
                <p>As children get older, it can be a challenge for them to get adequate daily physical activity. So we believe in inculcating sports from early childhood of a kid. Vincera Sports will become a organization where the spirit of sport is sown as a seed within kids from the younger age, which will make them achieve great heights in the field of sports. </p>
                <Vision/>
            </div>
            <div class="vision" style="background-color:transparent;">
                <Gallery/>
            </div>
            <!-- Clients -->
            <div class="vision">
                <label class="display-4" >Clients</label>
                <!-- <div class="subtitle">Clients</div> -->
                <div class="page-section">
                    <div class="container">
                        <div class="row">
                            <div class="column">
                            <!-- <div class="col-sm-6 col-lg-3 py-3 wow zoomIn"> -->
                                <div class="img-place client-img">
                                <img src="@/assets/clients/alter_sport.png" alt="">
                                </div>
                            </div>
                            <div class="column">
                            <!-- <div class="col-sm-6 col-lg-3 py-3 wow zoomIn"> -->
                                <div class="img-place client-img">
                                <img src="@/assets/clients/cleaning_service.png" alt="">
                                </div>
                            </div>
                            <div class="column">
                            <!-- <div class="col-sm-6 col-lg-3 py-3 wow zoomIn"> -->
                                <div class="img-place client-img">
                                <img src="@/assets/clients/creative_photo.png" alt="">
                                </div>
                            </div>
                            <div class="column">
                            <!-- <div class="col-sm-6 col-lg-3 py-3 wow zoomIn"> -->
                                <div class="img-place client-img">
                                <img src="@/assets/clients/global_tv.png" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div> <!-- End clients -->
            </div>
            <div class="whitecoloured"> 
                <label class="display-4" >Training Programs</label>
                    <!-- <div class="subtitle">Training Programs</div> -->
                <div class="position-realive bg-image">
                    <!-- <div class="page-section"> -->
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-5">
                                <!-- <div class="col-lg-5 py-3"> -->
                                    <div class="img-place wow zoomIn">
                                    <img src="@/assets/img/kids2.jpg" alt="">
                                    </div>
                                </div>
                                <div class="col-lg-6 fadeInUp">
                                <!-- <div class="col-lg-6 offset-lg-1 py-3 mt-lg-5 wow fadeInUp"> -->
                                    <h3 class="mb-4">FriskyKidz Program for Pre-School and Primary School</h3>
                                    <div class="mb-6">
                                        <p>Vincera programme is structured with lesson plans for all kids from KG to 5th standard with an aim to train the kids with best physical activities according to their age. We asses each kid in our Frisky kids program & we will also support the sports day event, after school program will also be conducted in the premises.</p>
                                        <p>Assessment will be conducted once in six months (Standing broad jump, Sit & Reach, Endurance test, Speed test, Overhead throw).</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    <!-- </div> -->
                    <!-- <div class="page-section"> -->
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-6 fadeInUp">
                                <!-- <div class="col-lg-6 offset-lg-1 py-3 mt-lg-10 wow fadeInUp" style="margin:8px"> -->
                                    <h3 class="mb-4">CORPORATE TRAINING</h3>
                                    <div class="mb-6">
                                    <p>Prolonged sitting is independently associated with negative health outcomes and mortality. But the health effects of prolonged sitting were most pronounced in people who never exercise or do so only occasionally.</p>
                                    <p>A person with high energy level inspires his co-workers and is more productive. A break is needed every one hour to avoid prolonged sitting.</p>
                                    <p>Fit employees tend to have better attitudes. Fit employees generally "feel good". They tend to have a physical and mental "balance" that results in a more positive attitude in the workplace.</p>
                                    <p>Fit employees are less stressed. Regular exercise releases the physical AND emotional tensions that life brings our way, thus a fit employee tends to have lower overall stress levels than an employee who does not engage in regular exercise.</p>
                                    <p>We offer training for corporate organizations where employees spend most of their in sitting front of the computer. We provide office workouts in your work area. Fitness activities are conducted every month. Beach workouts and hill workouts are also offered during weekends for employees.</p>
                                    <h5>Vincera Sports train employees for:</h5>
                                    <ul class='ullist'>
                                        <li>Office Workouts</li>
                                        <li>Stress Buster</li> 
                                        <li>Marathon</li>
                                        <li>Weight loss</li>
                                        <li>Fitness</li>
                                        <li>Diet</li>
                                    </ul>
                                    </div>
                                    <!-- <a href="#" class="btn btn-outline-primary rounded-pill">How it works</a> -->
                                </div>
                                <div class="col-lg-5">
                                <!-- <div class="col-lg-5 py-3"> -->
                                    <div class="img-place wow zoomIn">
                                    <img src="@/assets/img/kids3.jpg" alt="">
                                    </div>
                                </div>      
                            </div>
                        </div>
                    <!-- </div> -->
                </div>
            </div>
            <div class="vision">
                    <label class="display-4" >Complimentary Trails</label>
                    <p>We provide free training sessions for 1-2 weeks (comprising 3 sessions) as complimentary trials. You can avail all the free sessions to become acquainted with the training routines, the nature of training and our training process. Based on the complimentary trials, you can continue your training with our group.</p>
            </div>
            <div class="whitecoloured">
                <label class="display-4" >Training Exercises</label>
                    <p class="vision" style="background-color:transparent; margin-bottom:0px !important; padding: 1% 15% !important;margin-top:0px !important;">Our trainers utilize the best practices in athletics training and employ a systematic, scientific and holistic methodology. The training methodology essentially comprises of cardio and well-rounded routine activities, such as stretching, strength training, among others.</p>
                <div class="position-realive bg-image">
                    <div class="page-section" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                        <div class="container" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4"><span ></span> ANAEROBIC TRAINING</p>
                                    <p class="mb-8">Anaerobic training improves speed and power and involves speed runs of short distances on a range of terrains, including hills and synthetic surfaces.</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">INTERVAL TRAINING</p>
                                    <p class="mb-8">Interval training involves a short run in which running speed and intensity are varied at specific intervals. Interval training improves speed and cardiovascular fitness.</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">HILL WORKOUT</p>
                                    <p class="mb-8">Hill workouts consist of three variations: runs on short & steep hills, long & gradual hills and long & steep hills. Hill workouts improve your strength and speed.</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">FARTLEK TRAINING</p>
                                    <p class="mb-8">Fartlek is a Swedish term that means, “Speed Play”. Fartlek training involves a blend of continuous and interval training, and is more unstructured. Fartlek training improves your speed and anaerobic threshold.</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">AEROBIC TRAINING</p>
                                    <p class="mb-8">Aerobic training improves cardiovascular capacity, enhances cardio efficiency, conditions the muscles and builds endurance. It involves long, slow, continuous runs.</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">ASSESSMENT</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">CARDIO TRAINING</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">PERSONAL TRAINING</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">GROUP FITNESS</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">WEIGHT LOSS</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="vision">
                    <!-- <h2>Vision and Mission:</h2> -->
                <label class="display-4" >Marathon Trials</label>
                <!-- <div class="subtitle">MARATHON TRIALS</div> -->
                <p>We train enthusiasts for half marathon and full marathon. We train in groups outdoors in natural surroundings, providing you the opportunity to connect with nature and to meet and associate with like-minded people.</p>
                <p>Marathon running is typically accompanied by a specific training program. Runners may use a program that calls for four to six workouts per week, but there are times when you can only run three days per week. Running only three days per week has several benefits, including preventing injuries and overtraining, along with providing extra time for strength training workouts or recreational sports. Even though your schedule limits your training to three days per week, you can still cross the finish line of your next marathon.</p>
            </div>
            <div class="whitecoloured">
                <label class="display-4" >Training Methods</label>
                <!-- <div class="subtitle">Training Methods</div> -->
                <div class="position-realive bg-image">
                    <div class="page-section" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                        <div class="container" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">TIME FRAME</p>
                                    <p class="mb-8">By training only three days per week, the entire length of the half-marathon training program should last at least 12 to 16 weeks. This extended time frame allows enough time for your body to adapt and prepares your body for the physical challenges of the race. Each week will gradually progress in intensity to prepare your mind and body for race day, but will also develop a pattern for a lifetime of healthy running.</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">INTENSITY</p>
                                    <p class="mb-8">Intensity is the primary factor in a three-day training program. Each workout during the week has a specific focus and goal in mind, ranging from a speed workout, tempo run and long run. The speed workout incorporates short, high-intensity intervals such as 400 or 800 meter runs while the tempo run focuses on your goal pace in a three to five-mile run. The long run concludes the week and covers about 10 to 15 kms.</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">STRENGTH TRAINING</p>
                                    <p class="mb-8">Adding one to two days of strength training can supplement your running workouts for improved performance and overall fitness. You can mix the strength training workouts into the running workouts or supplement the workouts on alternating days. Use functional exercises that incorporate multiple muscle groups such as squats, deadlifts and lunges for the lower body and pullups, pushups and presses for the upper body.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="vision">
                    <!-- <h2>Vision and Mission:</h2> -->
                <label class="display-4" >Beep Test</label>
                <!-- <div class="subtitle">Beep Test</div> -->
                <p>The beep test is a physical fitness test of your aerobic fitness. To significantly improve your beep test score, you need to do specific and general aerobic type training. Although the aerobic energy system is primarily being tested, as in most activities it is not the sole energy source, and the anaerobic system (or speed endurance / lactate tolerance) also plays a part in the beep test performance as the speed increases and effort is required to slow down and accelerate away from each turn.</p>
            </div>
            <div class='kidstraining whitecoloured'>
                <label class="display-4" >Kids Training</label>
                <!-- <div class="subtitle">Kids Training</div> -->
                <!-- <div class="position-realive bg-image"> -->
                <h5 class="vision" style="background-color:transparent; margin-bottom:0px !important; padding: 1% 15% !important;margin-top:0px !important;">Methods of Training:</h5>
                <!-- </div> -->
                <div class="position-realive bg-image">
                    <div class="page-section" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                        <div class="container" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Cone drills</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Ladder drills</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Micro hurdles drills</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Running ABC</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Minor games</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Repetition method</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Continuous method</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Interval method</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Relays</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Plyometrics</p>
                                </div>
                            </div>
                            <div class="row" style="margin-top:0px !important; margin-bottom:0px !important; padding-top: 0px !important; padding-bottom: 0px !important;">
                                <div class="col-lg-10 offset-lg-1 py-3 mt-lg-5 wow fadeInUp">
                                    <p class="mb-4">Own body weight strength training</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="vision">
                <label class="display-4" >Fitness Program in your Resisdential Area</label>
                <!-- <div class="subtitle">Fitness Program in your residential area</div> -->
                <p>Vincera Sports comes at your doorstep. We conduct Fitness and wellness program for adults and kids. We give training for marathon, athletes, Basket ball and weight loss. We organize Sports day events and also offer Beach and Hill training.</p>
                <div>
                    <Residentareatraining/>
                </div>
            </div>    
            <!-- <p class="subtitle">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatem sunt fuga voluptates cumque dolore perspiciatis deleniti odit aperiam cupiditate qui, eligendi delectus eius repudiandae neque nostrum harum totam ea? Velit!</p>
            <button @click="chummaPo('/')">Click me</button> -->
    </div>   
    </div>
</template>

<script>
import Gallery from '~/components/Gallery.vue'
import Residentareatraining from '~/components/Residentareatraining.vue'
import Vision from '~/components/Vision.vue'

// import '~/assets/js/jquerymin.js'
// import '~/assets/js/bootstrapmin.js'
// import "~/assets/vendor/owl-carousel/js/owlcarouselmin.js"
// import "~/assets/vendor/wow/wowmin.js"
// import "~/assets/js/mobster.js"

export default {
  components: { Vision, Gallery, Residentareatraining },
    // data: function(){
    //     return{
    //         client:
    //     }
    // },
    methods:{
        chummaPo(param){
           this.$router.push(param)
        },
        chummaVa(){
            console.log("coming da")
        },
        processBullets() {
            var lastElement = false;
            $("br").remove(".tempbreak");
            $("ul li").each(function() {
                $(this).removeClass("nobullet");
                if (lastElement && lastElement.offset().top != $(this).offset().top) {
                    $(lastElement).addClass("nobullet");
                    $(lastElement).append('<br class="tempbreak" />');
                }
                lastElement = $(this);
            }).last().addClass("nobullet");
        }
    }
}
</script>

<style>
@import url('../assets/css/maicons.css');
/* @import url('../assets/vendor/owl-carousel/css/owlcarouselmin.css'); */
@import url('../assets/vendor/animate/animate.css');
@import url('../assets/css/bootstrap.css');
@import url('../assets/css/mobster.css');

/* .heading{
    font-size: 200px;
    color: blueviolet;
} */
/* .client-img img{
    padding: 12px;
    height: 100px;
    width: 150px;
} */

/* .ullist li { list-style: none; display: inline; }
.ullist li:after { content: " \00b7"; }
.ullist li:last-child:after { content: none; } */
*{
    /* font-size: 1.2vw; */
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
h5{
    font-size: 1.2vw;
    font-weight: bold;
}
h3{
    font-size: 1.8vw;
}
.display-4{
    font-size: 2.8vw;
    text-align: center !important;
    justify-content: center !important;
    display: block;
    /* padding-top:20px; */
    padding-bottom: 20px;
}
.whitecoloured{
    margin-top: 5%;
}
.ullist { width: 700px;}
.ullist li { display: inline; white-space: nowrap;} /*list-style-type: circle;}*/
.ullist li:after {
    content: " \00B7"; 
/* content: "&#9642;"; */
}
.ullist li:last-child::after { content: none; }
.col-lg-10 li{
    list-style: none;
}
.col-lg-10 p[class ='mb-4']::before {
    content: "\25C9"; /* Unicode bullet symbol */
    color:#ffcc00;  /* Bullet color */
	
	/* Optional tweaks */
    font-weight: bold;
    padding-right: 10px;
}
.col-lg-10 p[class ='mb-8']{
    padding-bottom: 0.5vw !important;
    margin-bottom: 0px !important;
}
.col-lg-10 p[class ='mb-4']{
    padding-bottom: 0.2vw !important;
    margin-bottom: 0px !important;
}
.kidstraining .mb-4, .mb-6{
    margin-bottom: 0px !important;
}
.col-lg-10{
    padding-top: 0px !important;
    margin-top: 0px !important;
    padding-bottom: 0vw !important;
    margin-bottom: 0.8vw !important;
}
.bg-image{
    background-image: url('../assets/img/pattern_1.svg');
}
.page-section {
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    padding-top: 0px !important;
    padding-bottom: 0px !important;
    margin-bottom: 0 !important;
}
.col-lg-5 img{
    /* border-radius: 12%; */
    width: auto !important;
    height: auto !important;
    /* box-shadow: #ffcc00; */
}
.col-lg-5, .page-section .col-lg-6{
    padding: 2%;
}
/* .page-section .col-lg-10{
    padding-top: 0px !important;
    padding-bottom: 0px !important;
    margin-bottom: 0.8vw !important;
} */
.mb-4{
    font-weight: bolder;
}

.main {
  /* padding: 16px; */
  /* margin-top: 30px; */
  /* height: 1500px; Used in this example to enable scrolling */
}
.vision{
  background-color: #ffcc00;
  justify-content: center;
  padding: 5% 15%;
  border-radius: 21px;
  /* display: block; */
}
/* img{
    border-radius: 21px;
} */
.label1{
    margin: auto;
    width: 23%;
    align-items: center;
    /* display: block; */
    font-size: 30px;
    /* line-height: 150%; */
    border-bottom: 3px solid black;
    padding: 10px;
}

.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
.fill {
    padding-top: 20px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    border-radius: 21px;
    max-height: 500px;
}
.fill img {
    flex-shrink: 0;
    min-width: 80%;
    min-height: 100%;
    width: 100%;
    /* padding: 12px; */
}
</style>