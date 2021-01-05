<template>
 <!-- <div class='navbar'>
    <ul>
        <li><label>Vincera</label></li>
        <li><a class='navright' href="#">About</a></li>
        <li><a class='navright' href="#">Contact</a></li>
        <li><a class='navright' href="#">Events</a></li>
    </ul>
 </div> -->
 <div>
   <nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#">Vincera</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
    <!-- <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form> -->
    <div class="navbar-collapse collapse w-100 order-3 dual-collapse2">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="#" @click="gotoevents()">Events</a>
            </li>
            <li class="nav-item">
                <a class="nav-link"  href="#" @click="gotocontactus()">Contact</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#" @click="gotoabout()">About</a>
            </li>
        </ul>
    </div>
</nav>
 </div>
</template>

<script>
// import Contactus from '~/pages/Contactus.vue';
export default {
  data:()=>({
    activeItem: 0
  }),
  methods:{
    gotocontactus(){
      this.$router.push('/Contactus');
    },
    gotoabout(){
      this.$router.push('/aboutus');
    },
    gotoevents(){
      this.$router.push('/new');
    }
  }
}
</script>
<style>
.navbar-brand{
  font-size: 30px;
  font-weight: bolder;
  font-family: 'Inter', sans-serif !important;
}
.navbar-light{
  background-color:lightsteelblue !important;
  /* background-color: white !important; */
}
.nav-item{
  padding: 0 15px !important;
  margin-bottom: 0px !important;
  /* color: white !important; */
}
/* ul {
  list-style-type: none;
  overflow: hidden;
  min-width: 100%;
}
.navbar{
    overflow: hidden;
    position: fixed;
    z-index: 10;
    top: 0;
    min-width: 100%;
    height: 0px;
    background-color: rgb(254, 252,239);
}
div{
    margin-bottom: 20px;
}

li .navright {
  float: right;
  font-size: 1.05vw;
  border: none;
}
li label{
    color: rgb(0, 0, 0);
    float: left;
    padding: 14px 36px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 30px;
    font-weight: bolder;
}
li a {
  display: block;
  color: rgb(0, 0, 0);
  text-align: center;
  padding-top: 25px;
  padding-bottom: 15px;
  padding: 20px 36px;
  text-decoration: none;
} */

/* Change the link color to #111 (black) on hover */
li a:hover {
  /* color: rgb(141, 141, 141); */
  /* text-decoration: none; */
  border-bottom:  3px solid rgb(0, 0, 0);
}
/* li{
  padding: 0px 12px;
} */
</style>