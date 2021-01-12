<template>
  <div id="app">
    <b-navbar toggleable="md" type="dark" class="nav-background">

    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

    <a class="navbar-brand" href="#">
    <img src="../assets/logo-coral.svg" alt="Logo" class="logo">
  
  </a>
<ul class="navbar-nav">
    <li class="nav-item">
      <a class="nav-link border_right" href="#"></a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-white align-self-center" href="#">Learn Jenkins from a DevOps Guru</a>
    </li>
    
  </ul>
 <b-collapse is-nav id="nav_collapse">

 <!-- Right aligned nav items -->

    <a class=" ml-auto d-flex">
    <div  id="page-content" class="align_self">
     <div >
             <div class="col-sm-3 col-md-4 col-6 circle-progress-block">
            <div id="circleProgress2" class="progressbar-js-circle p_bar">
              <svg viewBox="0 0 100 100" class="" >
             <path d="M 50,50 m 0,-48 a 48,48 0 1 1 0,96 a 48,48 0 1 1 0,-96" stroke="#eee" stroke-width="4" fill-opacity="0"></path>
            <path d="M 50,50 m 0,-48 a 48,48 0 1 1 0,96 a 48,48 0 1 1 0,-96" stroke="rgb(108,185,124)" stroke-width="4" fill-opacity="0" style="stroke-dasharray: 301.635, 301.635; stroke-dashoffset: 138.752;"></path>
          </svg>
         <div class="progressbar-text" style="position: absolute; left: 102%; top: 50%; padding: 0px; margin: 0px; transform: translate(-50%, -50%); color: rgb(0, 0, 0); font-size: 1rem;">
           <img style="width:18px"  src="../assets/cup.svg"/>
          </div>
           </div>
            </div>
            </div> 
            </div>
<div class="m-10">
<b-navbar-nav class="ml-auto">
 <b-nav-item-dropdown right>
        <!-- Using button-content slot -->
        <template slot="button-content" class="nounderline">
          <span class="text-white">Your progress</span>
        </template>
        <b-dropdown-item href="#" class="font-weight">155 of 361 complete.</b-dropdown-item>
        <b-dropdown-item href="#">Finish course to get your certificate</b-dropdown-item>
      </b-nav-item-dropdown>
    </b-navbar-nav>
</div>
</a>
      <div class=" border text-white border-white rounded-lg btn_share">
 <img class="flip" src="../assets/reply-white.svg"/>
   <span class="f_w">Share</span>
      </div>

    <div class="ml-1 border text-white border-white rounded-lg ">
 <img class="p_2" src="../assets/dot.svg"/>
  </div>
</b-collapse>
</b-navbar>
</div>
</template>

<script>
export default {
  name: 'app',
 
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css?family=Lato:400,700');

  body {
    background: #EEF1F4 !important;
    
  margin: 0;
  font-family: sf pro text,-apple-system,BlinkMacSystemFont,Roboto,segoe ui,Helvetica,Arial,sans-serif,apple color emoji,segoe ui emoji,segoe ui symbol;


  }
.nounderline {
  text-decoration: none !important;
  color: #EEF1F4;
}
  .nav-background {
    background: #353535;
  }
.logo{
 width: 100px;
object-fit: contain;

}
.border_right{
  border-right: 1px solid gray;
  margin: 14px;
}
.flip{
  transform: scale(-1,1);
    width: 20px;
    padding-bottom: 10px
}
.btn_share{
  padding: 0 13px;
}
 .flex {
     -webkit-box-flex: 1;
     -ms-flex: 1 1 auto;
     flex: 1 1 auto
 }

 @media (max-width:991.98px) {
     .padding {
         padding: 1.5rem
     }
 }

 @media (max-width:767.98px) {
     .padding {
         padding: 1rem
     }
 }

 .padding {
     padding: 5rem
 }

 .container {
     margin-top: 100px
 }

 .progress.progress-md {
     height: 8px
 }

 .template-demo .progress {
     margin-top: 1.5rem
 }

 .progress {
     border-radius: 3px;
     height: 8px
 }

 .pl-2,
 .px-2,
 .template-demo .circle-progress-block {
     padding-left: 0.5rem !important
 }

 .pr-2,
 .px-2,
 .template-demo .circle-progress-block {
     padding-right: 0.5rem !important
 }

 .mb-3,
 .template-demo .circle-progress-block,
 .my-3 {
     margin-bottom: 1rem !important
 }
 .p_bar{
     display: block;
     width: 30px;
 }
 .f_w{
     font-weight: 500;
     margin-left: 7px;
 }
 .align_self{
   align-self: center;
 }
.m-10{
  margin-left: -15px;
  margin-right: 10px;
}
.p_2{
  padding: 7px 1px;
}
.font-weight{
  font-weight: 700 !important;
}
</style>
