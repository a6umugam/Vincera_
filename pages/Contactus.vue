<template>
<div class="main">
    <!-- <div class="infobar">
        <h5>Important notification</h5>
        <p>50% off for new customers</p>
    </div> -->
    <Navbar/>
    <div class="container new-container bg-image">
        <Contact/>
    </div>
    <Footer/>
</div>
</template>

<script>
import Contact from '~/components/Contact.vue'
import Footer from '~/components/Footer.vue'
import Navbar from '~/components/Navbar.vue'
export default {
  components: { Navbar, Contact, Footer},

}
</script>
<style>
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