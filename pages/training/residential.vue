<template>
<div class="main">
    <Navbar/>
    <div class="container" style="padding-top: 150px; min-height: 100vh">
            <h2>Fitness Program in your Resisdential Area</h2>
            <p>Vincera Sports comes at your doorstep. We conduct Fitness and wellness program for adults and kids. We give training for marathon, athletes, Basket ball and weight loss. We organize Sports day events and also offer Beach and Hill training.</p>
            <Residentareatraining/>

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