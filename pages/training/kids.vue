<template>
<div class="main">
    <Navbar/>
    <div class="container" style="padding-top: 150px; min-height: 100vh">
           <div class="center">
                <h1>Kids training</h1>
           </div>
       

        <div class="center">
                <h1>METHODS OF TRAINING</h1>
               <div class="row">
            <div class="col-lg">
                <ul class='traingexer'>
                    <li>
                        <p class="mb-4">Cone drills</p>
                    </li>
                    <li>
                        <p class="mb-4">Ladder drills</p>
                    </li>
                    <li>
                        <p class="mb-4">Micro hurdles drills</p>
                    </li>
                    <li>
                        <p class="mb-4">Running ABC</p>
                    </li>
                    <li>
                        <p class="mb-4">Minor games</p>
                    </li>
                    <li>
                        <p class="mb-4">Repetition method</p>
                    </li>
                </ul>
            </div>
            <div class="col-lg">
                <ul class='traingexer'>
                    <li>
                        <p class="mb-4">Continuous method</p>
                    </li>
                    <li>
                        <p class="mb-4">Interval method</p>
                    </li>
                    <li>
                        <p class="mb-4">Relays</p>
                    </li>
                    <li>
                        <p class="mb-4">Plyometrics</p>
                    </li>
                    <li>
                        <p class="mb-4">Own body weight strength training</p>
                    </li>
                </ul>
            </div>
        </div>
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