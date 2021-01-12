<template>
<div id="app">
   <div class="e-main-content ">
<div class="bg-dark">
<mdb-container>
    <div class="embed-responsive embed-responsive-21by9">
      <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/vlDzYIIOYmM?enablejsapi=1&origin=https%3A%2F%2Fmdbootstrap.com"></iframe>
    </div>
    <button class="btn1">
<img src="../assets/navigate_before.svg" />
    </button>
    <button class="btn2">
      <img src="../assets/navigate_next.svg" />
    </button>
  </mdb-container>
</div>
<Info/>




          <div  id="button-align">
          <!-- <button ejs-button id="toggle2" class="e-btn e-info" v-on:click="rightToggle">Toggle Sidebar2</button> -->
 <button ejs-button  id="toggle2"  v-on:click="rightToggle"  type="button" class="course-content-toggle--button--RLfW6 btn btn-default--white">
<span >
  <img class="w_2" src="../assets/arrow.svg" />
</span>
<span class="course-content-toggle--label--IP79B text-white">Course content</span>
</button>
        </div>
</div>
     <ejs-sidebar class="t-7" id="default1" ref="rightsidebar" :width="width"  :position="position"
           :type="type">
           
    <div>        
<div class="title">
<div>
   <button ejs-button id="close" v-on:click="closeClick" class="e-btn close-btn close">
  <img src="../assets/close.svg" />
</button>
    </div>
<div class="sec_font">Course content </div>
</div>

   <div >
    <div class="d-flex card-t" v-on:click="isShowing= !isShowing">
<div class="d-flex flex-column align-items-baseline">
        <div class="d-flex justify-content-end">
        <span class="sec_font">Section 1: Getting started with Jenkins and All</span>
       
              <span v-if="isShowing" aria-hidden="true" class="ml-auto">
          <img src="../assets/arrow_up.svg"/>
</span>
        <span v-else aria-hidden="true" class="ml-auto">
          <img src="../assets/arrow_down.svg"/>
        </span>
       
        </div>
        <div>
          <span class="font-text-xs">14/14 | 33min</span>
        </div>
        </div>
 </div>
<div class="card-v" v-show="isShowing">
<div class="card-s">
<input type="checkbox" >
<span class="pl_13"> 1. ***Course FAQ's-*** (Must Watch)<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins

</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13"> 2. Social proof for  BEST SELLER in<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins
</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13">3. How to reach Trainer for Queries<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins
</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13">4. Jenkin syllabus
  <br>
<img class="pl-26" src="../assets/play_circle.svg"/>5mins</span><br>
</div>
</div>
</div>



   <div >
    <div class="d-flex card-t" v-on:click="isShowing2= !isShowing2">
<div class="d-flex flex-column align-items-baseline">
        <div class="d-flex justify-content-end">
        <span class="sec_font">Section 2: Complete Installation
    Guide for Jenkins</span>
              <span v-if="isShowing2" aria-hidden="true" class="ml-auto">
          <img src="../assets/arrow_up.svg"/>
</span>
        <span v-else aria-hidden="true" class="ml-auto">
          <img src="../assets/arrow_down.svg"/>
        </span>
       
        </div>
        <div>
          <span class="font-text-xs">12/12 | 33min</span>
        </div>
        </div>
 </div>
<div class="card-v" v-show="isShowing2">
<div class="card-s">
<input type="checkbox" >
<span class="pl_13"> 1. ***Course FAQ's-*** (Must Watch)<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13"> 2. Social proof for  BEST SELLER in<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13">3. How to reach Trainer for Queries<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13">4. Jenkin syllabus<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
</div>
</div>

   <div >
    <div class="d-flex card-t" v-on:click="isShowing1 = !isShowing1">
<div class="d-flex flex-column align-items-baseline">
        <div class="d-flex justify-content-end">
        <span class="sec_font">Section 3: Comtinuous Inspection with Jenkins</span>
       
              <span v-if="isShowing1" aria-hidden="true" class="ml-auto">
          <img src="../assets/arrow_up.svg"/>
</span>
        <span v-else aria-hidden="true" class="ml-auto">
          <img src="../assets/arrow_down.svg"/>
        </span>
       
        </div>
        <div>
          <span class="font-text-xs">3/4 | 14min</span>
        </div>
        </div>
 </div>
<div class="card-v" v-show="isShowing1">
<div class="card-s">
<input type="checkbox" >
<span class="pl_13"> 1. ***Course FAQ's-*** (Must Watch)<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13"> 2. Social proof for  BEST SELLER in<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13">3. How to reach Trainer for Queries<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
<div class="card-s">
<input type="checkbox" >
<span class="pl_13">4. Jenkin syllabus<br>
<img class="pl-26" src="../assets/play_circle.svg"/>10mins</span><br>
</div>
</div>
</div>
</div>
   </ejs-sidebar>
</div>
</template>
<script>
import Vue from 'vue';
import Info from "../components/Info.vue"
import { mdbContainer, mdbRow, mdbCol } from 'mdbvue';
import { SidebarPlugin } from '@syncfusion/ej2-vue-navigations';
import { ButtonPlugin } from '@syncfusion/ej2-vue-buttons';
import { enableRipple } from '@syncfusion/ej2-base';
enableRipple(true);

Vue.use(SidebarPlugin);
Vue.use(ButtonPlugin);
export default {
  components: {
    mdbContainer,
    mdbRow,
    mdbCol,
    Info
   
  },
       data () {
         
        return {
         width : '350px',
         position: 'Right',
         type: 'Push',
        isShowing:false,
         isShowing1:false,
          isShowing2:false,
     };
     },
     methods: {
     rightToggle: function() {
         this.$refs.rightsidebar.toggle();
        
         },
        
        closeClick: function() {
         this.$refs.rightsidebar.hide();
        }
        
    }
}
</script>
<style>
@import  url("../../node_modules/@syncfusion/ej2-vue-navigations/styles/material.css");

.e-main-content{
    text-align: center;
    height: auto;
    background: white;
    font-size: 16px;
    padding: 100px;
}

#button-align{
    padding: 15px;
}

.title {
    background-color: white;
    color: black;
    font-size: 20px;
    padding: 15px;
}

#default,#default1 {
    background-color: white;
    color: #ffffff;
    overflow: hidden;
    top: 60px;
     border:none;
}
.t-7{
  top:7%
}
.course-content-toggle--button--RLfW6 {
    position: absolute;
    background-color: rgba(41,48,59,.7)!important;
    border: none;
    border-radius: 0;
    pointer-events: auto;
    padding: 8px 16px;
    margin-top: 16px;
    height: 50px;
    max-width: 150px;
    width: auto;
    right: 0;
    top: 0;
    z-index: 10;
    transition: all 1s ease-in-out;
}

.btn-default--white {
    color: #fff;
    background-color: transparent;
    border: 1px solid #fff;
}

.btn {
    display: inline-block;
    margin-bottom: 0;
    font-weight: 700;
    text-align: center;
    vertical-align: middle;
    touch-action: manipulation;
    cursor: pointer;
    background-image: none;
    border: 1px solid transparent;
    white-space: nowrap;
    padding: 11px 12px;
    font-size: 15px;
    line-height: 1.35135;
    border-radius: 2px;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

button, html input[type=button], input[type=reset], input[type=submit] {
    -webkit-appearance: button;
    cursor: pointer;
}

button, select {
    text-transform: none;
}

button {
    overflow: visible;
}
.course-content-toggle--button--RLfW6:not(:hover) .course-content-toggle--label--IP79B {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0,0,0,0);
    border: 0;
}
.w_2{
  width: 25px;
}
.close{
  border: none;
    background-color: transparent;
}
.btn-secondary {
    color:black !important;
    background-color: #ffffff !important;
    border-color: #6c757d !important;
}
.sec_font{
font-size: 15px;
    font-weight: 700;
    line-height: 1.43em;
    padding-right: 25px;
}
.font-text-xs {
    font-size: 12px;
    font-weight: 400;
    line-height: 1.33em;
}

.pl_13{
padding-left: 13px;
}
.pl-26{
  padding-left: 26px;
}
.card-t{
  position: relative;
  flex-wrap: wrap;
   color: black;
    border: 1px solid #dedfe0;
    padding: 16px;
    background: #f7f7f7;
}
.card-v{
  position: relative;
  flex-wrap: wrap;
   color: black;
    box-shadow: 0 0px 0px 4px rgba(50, 50 , 93, .25);
   
}
.card-s{
  position: relative;
  flex-wrap: wrap;
  padding: 16px;
}
.card-s:hover{
  background: #e6f2f5;
}
.e-main-content{
  padding:0 !important
}
.container {
    margin-top:0 !important ;
}
.btn1 {
  position: absolute;
  top: 20%;
  left: 2%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  background-color: #555;
  color: white;
  font-size: 16px;
  padding: 10px 7px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  text-align: center;
}

.btn1:hover {
  background-color: black;
}
.btn2 {
  position: absolute;
  top: 20%;
  right: 0;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  background-color: #555;
  color: white;
  font-size: 16px;
  padding: 10px 7px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  text-align: center;
}

.btn2:hover {
  background-color: black;
}
</style>