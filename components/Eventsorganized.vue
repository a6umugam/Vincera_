<template>
    <div>
        <div class="row">
            <h4>Kids Athletic  Meet</h4>
            <p>Our first  event  kids athletic meet  2019  was  successfully conducted  on  August 25th 2019  at Jawharlal  Nehru  Stadium  for kids  from  UKG TO  VII  STD. 2 5+  schools participated .  No of  students  participated  1200+  & footfall of 2500+</p>
        </div>
        <div class="row">
            <div class="column">
            <img src="~/assets/img/eventsmarathon1.png" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
            <img src="~/assets/img/eventsmarathon2.png" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
            <img src="~/assets/img/eventsmarathon3.png" style="width:100%" class="hover-shadow cursor">
            </div>
        </div>
        <div class="row">
          <h4>GAGNER SOCIAL  MARATHON 2020 (Run for  old age home &  Special children)</h4>
            <p>Our second  event   gagner  social Marathon  2020  was  conducted  on  2 nd February,2020  at  Elliot’s Beach  Besant  Nagar.  This marathon  was conducted  to support  old  age  home  & Special children. We had more than 900 participants and  foot  fall  of 1800+</p>
        </div>
        <div class="row">
            <div class="column">
            <img src="~/assets/img/eventsorganized2.png" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
            <img src="~/assets/img/eventsorganized1.png" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
            <img src="~/assets/img/eventsorganized3.png" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
            <img src="~/assets/img/eventsorganized4.png" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
            <img src="~/assets/img/eventsorganized5.png" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
            <img src="~/assets/img/eventsorganized6.png" style="width:100%" class="hover-shadow cursor">
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

.column {
  float: left;
  width: 25%;
}

/* The Modal (background) */
.modal {
  display: none;
  position: fixed;
  z-index: 1;
  padding-top: 100px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: black;
}

/* Modal Content */
.modal-content {
  position: relative;
  background-color: #fefefe;
  margin: auto;
  padding: 0;
  width: 90%;
  max-width: 1200px;
}

/* The Close Button */
.close {
  color: white;
  position: absolute;
  top: 10px;
  right: 25px;
  font-size: 35px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: #999;
  text-decoration: none;
  cursor: pointer;
}

.mySlides {
  display: none;
}

.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

img {
  margin-bottom: -4px;
}

.caption-container {
  text-align: center;
  background-color: black;
  padding: 2px 16px;
  color: white;
}

.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}

img.hover-shadow {
  transition: 0.3s;
}

.hover-shadow:hover {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
</style>