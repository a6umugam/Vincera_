<template>
<div class="main">
    <Navbar/>
    <div class="container" style="padding-top: 150px; min-height: 100vh">
           <div class="center">
                <h1>CORPORATE TRAINING</h1>
           </div>
       <div class="row">
            <div class="col-lg-8 trpg">
                <!-- <h6 class='mb-4'>CORPORATE TRAINING</h6> -->
                <div class='mb-8'>
                    <p>Prolonged sitting is independently associated with negative health outcomes and mortality. But the health effects of prolonged sitting were most pronounced in people who never exercise or do so only occasionally.</p>
                    <p>A person with high energy level inspires his co-workers and is more productive. A break is needed every one hour to avoid prolonged sitting.</p>
                    <p>Fit employees tend to have better attitudes. Fit employees generally "feel good". They tend to have a physical and mental "balance" that results in a more positive attitude in the workplace.</p>
                    <p>Fit employees are less stressed. Regular exercise releases the physical AND emotional tensions that life brings our way, thus a fit employee tends to have lower overall stress levels than an employee who does not engage in regular exercise.</p>
                    <p>We offer training for corporate organizations where employees spend most of their in sitting front of the computer. We provide office workouts in your work area. Fitness activities are conducted every month. Beach workouts and hill workouts are also offered during weekends for employees.</p>
                    <p class='listhead'>Vincera Sports train employees for:</p>
                    <ul class='ullist'>
                        <li>Office Workouts</li>
                        <li>Stress Buster</li> 
                        <li>Marathon</li>
                        <li>Weight loss</li>
                        <li>Fitness</li>
                        <li>Diet</li>
                    </ul>
                </div>
            </div>
            <div class="col">
                <img src="~/assets/img/corp1.jpg" style="width:100%" class="hover-shadow cursor">
                <img src="~/assets/img/corp2.jpg" style="width:100%" class="hover-shadow cursor">
                <img src="~/assets/img/corp3.jpg" style="width:100%" class="hover-shadow cursor">
            </div>
        </div>

        <div class="center">
                <h1>COMPLIMENTARY TRIALS</h1>
                <p>We provide free training sessions for 1-2 weeks (comprising 3 sessions) as complimentary trials. You can avail all the free sessions to become acquainted with the training routines, the nature of training and our training process. Based on the complimentary trials, you can continue your training with our group.</p>
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
@media only screen and (max-width: 800px) {
    

}
</style>