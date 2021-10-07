<template>
<div class="main">
    <Navbar/>
    <div class="container" style="padding-top: 150px; min-height: 100vh">
           <div class="center">
                <h1>Fitness Training</h1>
           </div>
           <h2>TRAINING EXERCISES</h2>

       <div class="row">
            <div class="col-lg">
                <p>Our trainers utilize the best practices in athletics training and employ a systematic, scientific and holistic methodology. The training methodology essentially comprises of cardio and well-rounded routine activities, such as stretching, strength training, among others.</p>
            </div>
        </div>
        <div class="row">
            <ul class='traingexer'>
                <li>
                    <p class="mb-4">ANAEROBIC TRAINING</p>
                    <p class="mb-8">Anaerobic training improves speed and power and involves speed runs of short distances on a range of terrains, including hills and synthetic surfaces.</p>
                </li>
                <li>
                    <p class="mb-4">INTERVAL TRAINING</p>
                    <p class="mb-8">Interval training involves a short run in which running speed and intensity are varied at specific intervals. Interval training improves speed and cardiovascular fitness.</p>
                </li>
                <li>
                    <p class="mb-4">HILL WORKOUT</p>
                    <p class="mb-8">Hill workouts consist of three variations: runs on short & steep hills, long & gradual hills and long & steep hills. Hill workouts improve your strength and speed.</p>
                </li>
                <li>
                    <p class="mb-4">FARTLEK TRAINING</p>
                    <p class="mb-8">Fartlek is a Swedish term that means, “Speed Play”. Fartlek training involves a blend of continuous and interval training, and is more unstructured. Fartlek training improves your speed and anaerobic threshold.</p>
                </li>
                <li>
                    <p class="mb-4">AEROBIC TRAINING</p>
                    <p class="mb-8">Aerobic training improves cardiovascular capacity, enhances cardio efficiency, conditions the muscles and builds endurance. It involves long, slow, continuous runs.</p>
                </li>
                <li>
                    <p class="mb-4">ASSESSMENT</p>
                </li>
                <li>
                    <p class="mb-4">CARDIO TRAINING</p>
                </li>
                <li>
                    <p class="mb-4">PERSONAL TRAINING</p>
                </li>
                <li>
                    <p class="mb-4">GROUP FITNESS</p>
                </li>
                <li>
                    <p class="mb-4">WEIGHT LOSS</p>
                </li>
            </ul>
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
    border-radius: 10px;
}

.traingexer li{
    list-style: none;
}
.traingexer p[class ='mb-4']{
    font-weight: bold;
    font-family: 'Trebuchet MS';
}
.traingexer p[class ='mb-8']{
    padding-left: 30px;
}
.traingexer p[class ='mb-4']::before {
    content: "\25C9"; /* Unicode bullet symbol */
    color:#ffcc00;  /* Bullet color */
	/* Optional tweaks */
    font-weight: bold;
    padding: 10px;
}

@media only screen and (max-width: 800px) {
    

}
</style>