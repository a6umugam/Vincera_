<template>
    <div class="row">
        <ul class='traingexer'>
            <li>
                <p class="mb-4">TIME FRAME</p>
                <p class="mb-8">By training only three days per week, the entire length of the half-marathon training program should last at least 12 to 16 weeks. This extended time frame allows enough time for your body to adapt and prepares your body for the physical challenges of the race. Each week will gradually progress in intensity to prepare your mind and body for race day, but will also develop a pattern for a lifetime of healthy running.</p>
            </li>
            <li>
                <p class="mb-4">INTENSITY</p>
                <p class="mb-8">Intensity is the primary factor in a three-day training program. Each workout during the week has a specific focus and goal in mind, ranging from a speed workout, tempo run and long run. The speed workout incorporates short, high-intensity intervals such as 400 or 800 meter runs while the tempo run focuses on your goal pace in a three to five-mile run. The long run concludes the week and covers about 10 to 15 kms.</p>
            </li>
            <li>
                <p class="mb-4">STRENGTH TRAINING</p>
                <p class="mb-8">Adding one to two days of strength training can supplement your running workouts for improved performance and overall fitness. You can mix the strength training workouts into the running workouts or supplement the workouts on alternating days. Use functional exercises that incorporate multiple muscle groups such as squats, deadlifts and lunges for the lower body and pullups, pushups and presses for the upper body.</p>
            </li>
        </ul>
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