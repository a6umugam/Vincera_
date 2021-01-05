<template>
  <div class="main">
    <!-- <div class="infobar">
        <h5>Important notification</h5>
        <p>50% off for new customers</p>
    </div> -->
    <Navbar/>
    <img class="image" v-for="(image, i) in images" :src="image" :key="i" @click="index = i">
    <!-- <vue-gallery-slideshow :images="images" :index="index" @close="index = null"></vue-gallery-slideshow> -->
    <!-- <vueglleryslideshow :images="images" :index="index" @close="index = null"></vueglleryslideshow> -->
    <div class="container new-container bg-image">
        <div class="new-only-text" style="margin-top:21px">
            <h2>About Vincera</h2>
            <p>Vincera Sports is aimed at inculcating the value of sport in kids and adults. We offer the Best-in-Class Sports program for kids and adults.  Every child can be successful at one sport or another. However, it takes time for parents to find the sport suitable for the child. Therefore, they should be patient in selecting the sports, since it is a process that will pay off in the long run. Here in Vincera Sports, we help you to find the hidden skill in your child and employ techniques and strategies to develop the fine and gross motor skills in them.</p>
            <p>Prolonged sitting is independently associated with negative health outcomes and mortality. So corporate organizations are making fitness a part of their employees lifestyle. We at Vincera Sports train their employees as part of the employee wellness program.</p>
            <h1>"Sit Less. Move More. Play Together."</h1>
        </div>
    </div>
    <!-- <div id="app"> -->
        
    <!-- </div> -->
    <Footer/>
  </div>
</template>

<script>
import Footer from '~/components/Footer.vue'
import Navbar from '~/components/Navbar.vue'
// import vueglleryslideshow from '~/assets/js/vueglleryslideshow.js'
// import VueGallerySlideshow from 'vue-gallery-slideshow'
export default {
  components: { Navbar, Footer },
  data: {
    images: [
      'https://placekitten.com/801/800',
      'https://placekitten.com/802/800',
      'https://placekitten.com/803/800',
      'https://placekitten.com/804/800',
      'https://placekitten.com/805/800',
      'https://placekitten.com/806/800',
      'https://placekitten.com/807/800',
      'https://placekitten.com/808/800',
      'https://placekitten.com/809/800',
      'https://placekitten.com/810/800'
    ],
    index: null
  }

}
</script>

<style>
.image {
  width: 100px;
  height: 100px;
  background-size: cover;
  cursor: pointer;
  margin: 5px;
  border-radius: 3px;
  border: 1px solid lightgray;
  object-fit: contain;
}
.infobar{
    display: flex;
    width: 100%;
    /* background-color: peru; */
    /* background-color: royalblue; */
    /* color: white; */
    color: #000;
    justify-content: space-between;
    padding: 3px 30px 3px 30px;
    align-items: center;
}

.infobar p{
    margin-bottom: 0px;
}
</style>