<template>
    <div>
        <div class="row">
            <div class="col-lg-6 trpg">
                <h6 class='mb-4'>FriskyKidz Program for Pre-School and Primary School</h6>
                <div class='mb-8'>
                    <p>Vincera programme is structured with lesson plans for all kids from KG to 5th standard with an aim to train the kids with best physical activities according to their age. We asses each kid in our Frisky kids program & we will also support the sports day event, after school program will also be conducted in the premises.</p>
                    <p>Assessment will be conducted once in six months (Standing broad jump, Sit & Reach, Endurance test, Speed test, Overhead throw).</p>
                </div>
            </div>
            <div class="col-lg-4 trpg">
                <img src="~/assets/img/kids2.jpg" style="width:100%" class="hover-shadow cursor">
            </div>
        </div>
        <div class="row">
            <div class="col-lg-4 trpg">
                <img src="~/assets/img/kids5.jpg" style="width:100%" class="hover-shadow cursor">
                <img src="~/assets/img/kids6.jpg" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="col-lg-6 trpg">
                <h6 class='mb-4'>CORPORATE TRAINING</h6>
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
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.row > .column {
  padding: 0 8px;
}
.row{
    padding-top: 30px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
.ullist { width: 100%;}
.ullist li { display: inline; white-space: nowrap;} /*list-style-type: circle;}*/
.ullist li:after {
    content: " \00B7"; 
/* content: "&#9642;"; */
}
.ullist li:last-child::after { content: none; }
.listhead {
  font-weight: bold;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.cursor {
  cursor: pointer;
}

img {
  margin-bottom: -4px;
}

img.hover-shadow {
  transition: 0.3s;
}

.hover-shadow:hover {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
</style>