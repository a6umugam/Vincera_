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
  <a class="navbar-brand" @click="goto('/')"> <img src="~/assets/logo.png" alt="Logo" width="10%"> Vincera</a>
  <button class="navbar-toggler" @click="menuActive = !menuActive" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
    <!-- <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form> -->
    <div class="navbar-collapse collapse w-100 order-3 dual-collapse2">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link"  @click="goto('/')">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link"  @click="goto('/events')">Events</a>
            </li>
            <li class="nav-item">
                <a class="nav-link"  @click="goto('/programs')">Training</a>
            </li>
            <li class="nav-item">
                <a class="nav-link"   @click="goto('/contactus')">Contact</a>
            </li>
            <li class="nav-item">
                <a class="nav-link"   @click="goto('/aboutus')">About</a>
            </li>
        </ul>
    </div>
</nav>

<div class="menu-mobile" v-if="menuActive">
            <div>
                <a    @click="goto('/')">Home</a>
            </div>
            <div>
                <a    @click="goto('/events')">Events</a>
            </div>
            <div >
                <a   @click="goto('/programs')">Training</a>
            </div>
            <div >
                <a   @click="goto('/contactus')">Contact</a>
            </div>
            <div>
                <a   @click="goto('/aboutus')">About</a>
            </div>
</div>
 </div>
</template>

<script>
// import Contactus from '~/pages/Contactus.vue';
export default {
  data(){
    return{
      menuActive: false
    }
  },
  methods:{
    goto(parm){
      this.$router.push(parm);
    },
  }
}
</script>
<style>
.menu-mobile{
        display: none;
    flex-flow: column;
    justify-content: space-evenly;
    align-items: center;
    margin-bottom: 15px;
    height: 200px;
    font-weight: bolder;
}

.nav-mobile div{
  margin-top: 4px;
  cursor: pointer;
  }
/* .navbar-brand{
      display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
}
.navbar-light{
  display: flex;
  background-color:white !important;
   box-shadow: 0 8px 6px -6px #999;
   height: 85px;
}
.nav-item{
  padding: 0 15px !important;
  margin-bottom: 0px !important;
  cursor: pointer;
} */
  /* color: white !important; */
.navbar-brand{
  font-size: 30px;
  font-weight: bolder;
  /* font-family: 'Inter', sans-serif !important; */
  background: linear-gradient(to right, red, purple);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  color:transparent;
}
.navbar-light{
  /* background-color:lightsteelblue !important; */
  background-color: black !important;
}
.nav-item{
  padding: 0 15px !important;
  margin-bottom: 0px !important;
  /* color: white !important; */
}
.nav-item a{
  color: white !important;
}
.navbar{
  overflow: hidden;
  position: fixed; /* Set the navbar to fixed position */
  top: 0; /* Position the navbar at the top of the page */
  width: 100%; /* Full width */
  z-index: 10;
}

li a:hover {
  border-bottom:  3px solid rgb(160, 17, 64);
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
/* li a:hover { */
  /* color: rgb(141, 141, 141); */
  /* text-decoration: none; */
  /* border-bottom:  3px solid rgb(255, 0, 0);
  transition: 0.3s;
} */
/* li{
  padding: 0px 12px;
} */

@media only screen and (max-width: 800px) {
  .menu-mobile{
    display: flex
  }
  }
</style>