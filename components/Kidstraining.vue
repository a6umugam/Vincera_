<template>
    <div>
        <div class="row">
            <div class="col-lg">
                <h5>Methods of Training:</h5>
            </div>
        </div>
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
</template>

<script>
export default {

}
</script>

<style>
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
</style>