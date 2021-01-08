<template>
  <div>
          <!-- <label class='display-4' style="text-align:center">Gallery</label> -->
        <div class="row">
            <div class="column">
                <img :src="image1" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
                <img :src="image2" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
                <img :src="image1" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
                <img :src="image2" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
                <img :src="image1" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
                <img :src="image2" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
                <img :src="image1" style="width:100%" class="hover-shadow cursor">
            </div>
            <div class="column">
                <img :src="image2" style="width:100%" class="hover-shadow cursor">
            </div>
        </div>
        <div id="myModal" class="modal">
        <span class="close cursor" @click="closeModal()">&times;</span>
            <div class="mySlides">
            <div class="numbertext">1 / 4</div>
            <img :src="image1" style="width:100%">
            </div>

            <div class="mySlides">
            <div class="numbertext">2 / 4</div>
            <img :src="image1" style="width:100%">
            </div>
        </div>
  </div>
</template>

<script>
import image1 from '~/assets/pic1.jpg';
import image2 from '~/assets/pic2.jpg';
var slideIndex = 1;
export default {
    data: function () {
            // showSlides(slideIndex);
            return {
                image1: image1,
                image2: image2,
            }
        },
    methods:{
         openModal() {
        document.getElementById("myModal").style.display = "block";
        },
        closeModal() {
        document.getElementById("myModal").style.display = "none";
        },
        // plusSlides(n) {
        // showSlides(slideIndex += n);
        // },
        // currentSlide(n) {
        // showSlides(slideIndex = n);
        // },
        // showSlides(n) {
        // var i;
        // var slides = document.getElementsByClassName("mySlides");
        // var dots = document.getElementsByClassName("demo");
        // var captionText = document.getElementById("caption");
        // if (n > slides.length) {slideIndex = 1}
        // if (n < 1) {slideIndex = slides.length}
        // for (i = 0; i < slides.length; i++) {
        //     slides[i].style.display = "none";
        // }
        // for (i = 0; i < dots.length; i++) {
        //     dots[i].className = dots[i].className.replace(" active", "");
        // }
        // slides[slideIndex-1].style.display = "block";
        // dots[slideIndex-1].className += " active";
        // captionText.innerHTML = dots[slideIndex-1].alt;
        // }
    }
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
.label{
    margin: auto;
    width: 10%;
    align-items: center;
    /* display: block; */
    font-size: 30px;
    /* line-height: 150%; */
    border-bottom: 3px solid black;
    padding: 10px;
}

.column {
  float: left;
  width: 25%;
  border-radius: 8px;
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
  padding-bottom: 21px;
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