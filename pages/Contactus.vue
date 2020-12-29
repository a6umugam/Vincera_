<template>
<div class="main">
    <div class="infobar">
        <h5>Important notification</h5>
        <p>50% off for new customers</p>
    </div>
    <Navbar/>
    <div class="container new-container bg-image">
        <Contact/>
    </div>
</div>
</template>

<script>
import Contact from '~/components/Contact.vue'
import Navbar from '~/components/Navbar.vue'
export default {
  components: { Navbar },

}
</script>

<style
Contact>

</style>