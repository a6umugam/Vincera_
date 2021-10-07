<template>
<div class="main">
    <Navbar/>
    <div class="container" style="padding-top: 150px; min-height: 100vh">
           <div class="center">
                <h1>Marathon Training</h1>
                <p>We train enthusiasts for half marathon and full marathon. We train in groups outdoors in natural surroundings, providing you the opportunity to connect with nature and to meet and associate with like-minded people.</p>
                <p>Marathon running is typically accompanied by a specific training program. Runners may use a program that calls for four to six workouts per week, but there are times when you can only run three days per week. Running only three days per week has several benefits, including preventing injuries and overtraining, along with providing extra time for strength training workouts or recreational sports. Even though your schedule limits your training to three days per week, you can still cross the finish line of your next marathon.</p>

           </div>
                    

        <div class="center">
            <h2>TRAINING METHODS</h2>
        </div>

        <div class="center">
            <h3>TIME FRAME</h3>
            <p>By training only three days per week, the entire length of the half-marathon training program should last at least 12 to 16 weeks. This extended time frame allows enough time for your body to adapt and prepares your body for the physical challenges of the race. Each week will gradually progress in intensity to prepare your mind and body for race day, but will also develop a pattern for a lifetime of healthy running.</p>
        </div>

        <div class="center">
            <h3>INTENSITY</h3>
            <p>Intensity is the primary factor in a three-day training program. Each workout during the week has a specific focus and goal in mind, ranging from a speed workout, tempo run and long run. The speed workout incorporates short, high-intensity intervals such as 400 or 800 meter runs while the tempo run focuses on your goal pace in a three to five-mile run. The long run concludes the week and covers about 10 to 15 kms.</p>
        </div>

        <div class="center">
            <h3>STRENGTH TRAINING</h3>
            <p>Adding one to two days of strength training can supplement your running workouts for improved performance and overall fitness. You can mix the strength training workouts into the running workouts or supplement the workouts on alternating days. Use functional exercises that incorporate multiple muscle groups such as squats, deadlifts and lunges for the lower body and pullups, pushups and presses for the upper body.</p>
        </div>

        <div class="center">
            <h3>Beep Test</h3>
            <p>The beep test is a physical fitness test of your aerobic fitness. To significantly improve your beep test score, you need to do specific and general aerobic type training. Although the aerobic energy system is primarily being tested, as in most activities it is not the sole energy source, and the anaerobic system (or speed endurance / lactate tolerance) also plays a part in the beep test performance as the speed increases and effort is required to slow down and accelerate away from each turn.</p>
        </div>

        <div class="center">
            <h3>Beach Training </h3>
            <p>The beep test is a physical fitness test of your aerobic fitness. To significantly improve your beep test score, you need to do specific and general aerobic type training. Although the aerobic energy system is primarily being tested, as in most activities it is not the sole energy source, and the anaerobic system (or speed endurance / lactate tolerance) also plays a part in the beep test performance as the speed increases and effort is required to slow down and accelerate away from each turn.</p>
            <img src="~assets/img/beach1.jpg" alt="methods">
            <img src="~assets/img/beach2.jpg" alt="methods">

        </div>

    </div>
    <div>
        <Footer/>
    </div>
</div>
  
</template>

<script>

</script>

<style>

.main{
  background-image: url('~assets/img/Rainbow-Vortex.svg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  color: aliceblue;
}

.center{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    padding-bottom: 50px;
    flex-flow: column;
}

.center h1{
    font-weight: bold;
}

.center img{
    /* width: 100%; */
    max-width: 100%;
    border-radius: 10px;
    padding-bottom: 20px;
}
@media only screen and (max-width: 800px) {
    

}
</style>