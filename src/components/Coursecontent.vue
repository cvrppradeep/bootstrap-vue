<template>
<div class="">
    <center>
<div>
     <div class="d-flex card-t w-33" v-on:click="isShowing= !isShowing">
<div class="d-flex flex-column align-items-baseline">
        <div class="d-flex justify-content-end">
        <span class="sec_font">Section 1: Getting started with Jenkins</span>
       
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
<div class="card-v w-33" v-show="isShowing">
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
    <div class="d-flex card-t w-33" v-on:click="isShowing2= !isShowing2">
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
<div class="card-v w-33" v-show="isShowing2">
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








    </center>
    <Footer/>
</div>
</template>
<script>
import Footer from "../components/Footer.vue";
export default {
     components: {
   Footer

   
  },
       data () {
         
        return {
       
        isShowing:false,
         isShowing1:false,
          isShowing2:false,
     };
}
}
</script>
<style scoped>
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
.w-33{
    width: 33% !important;
}
</style>