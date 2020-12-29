<template>
    <div class="quote">
        <span class="left">❝</span>
        <blockquote>
            Sit Less. Move More. Play Together.
        </blockquote>
        <!-- <small>Francis of Assisi</small> -->
        <span class="right">❞</span>
    </div>
</template>

<script>
export default {

}
</script>

<style>
template{
    background-color:#ffcc00;
    justify-content: center;
}
/* .vision{
  background-color: #ff0095;
  justify-content: center;
  margin: 10px 10px;
} */
.quote{
  text-align: center;
  font-size: 2.3vw;
  /* margin: auto; */
  margin-left: 20%;
  margin-right: 20%;
  border: 2px solid black;
  max-width: 30%;
  position: relative;
  margin-top: 5vw;
  margin-bottom: 5vw;
}
blockquote{
  color: white;
  font-family:'Courier New', Courier, monospace;
  font-style: italic;
  position: relative;
  z-index: 8;
}
.left{
  position: absolute;
  top: -50px;
  left: -20px;
  width: 50px;
  text-align: left;
  z-index: 5;
  font-size: 3.5vw;
  color: #336699;
  background-color: #ffcc00;
  line-height: 130px;
}
.right{
  position: absolute;
  bottom: -50px;
  right: -20px;
  width: 50px;
  text-align: right;
  z-index: 5;
  font-size: 3.5vw;
  color: #336699;
  background-color: #ffcc00;
  line-height: 130px;
}
/* small{
  font-size: 1.7rem;
  color: #336699;
  position: relative;
  z-index: 20;
}
  
  small:before{
    content: "\2014 \0020";
    width: 5px;
  } */

</style>