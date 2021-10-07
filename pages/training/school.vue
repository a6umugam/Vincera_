<template>
<div class="main">
    <Navbar/>
    <div class="container" style="padding-top: 150px; min-height: 100vh">
           <div class="center">
                <h1>IN-SCHOOL PROGRAM</h1>
           </div>
       <div class="row">
            <div class="col-lg-8 trpg">
                <h3 class='mb-4'>FriskyKidz Program for Pre-School and Primary School</h3>
                <div class='mb-8'>
                    <p>Vincera programme is structured with lesson plans for all kids from KG to 5th standard with an aim to train the kids with best physical activities according to their age. We asses each kid in our Frisky kids program & we will also support the sports day event, after school program will also be conducted in the premises.</p>
                    <p>Assessment will be conducted once in six months (Standing broad jump, Sit & Reach, Endurance test, Speed test, Overhead throw).</p>
                </div>
            </div>
            <div class="col">
                <img src="~/assets/img/kids2.jpg" style="width:100%" class="hover-shadow cursor">
            </div>
        </div>

        <div class="center">
                <h1>METHODS OF TRAINING</h1>
                <img src="~assets/img/methods1.png" alt="methods">
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