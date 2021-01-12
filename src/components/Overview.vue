<template>
    <div  class="d-flex flex-column pt-4 p_4 align-items-baseline">
    <div class="fnt">
        <h2>About this course</h2>
  </div>
    <div>
<p class="fnt_1">

    "TOP RATED (BEST SELLER) #1 Master SELENIUM java course" -5 Million students learning worldWide with great collaboration
</p>

    </div>
<div class="border_tb fnt_1 w-100">
<div class="d-flex justify-content-between p-4">
<div>By the numbers</div>
<div class="d-flex flex-column fnt_1">
<div>Skill level: All Levels</div>
<div>Students: 162263</div>
<div>Languages: English</div>
<div>Captions: Yes</div>
</div>
<div class="d-flex flex-column fnt_1">
    <div>Lectures: 350</div>
    <div>Video: 54.5 total hours</div>
    </div>
</div>
</div>

<div class="border_tb fnt_1 w-100">
<div class="d-flex justify-content-between p-4">
<div>Certificates</div>
<div class="d-flex flex-column fnt_1">
<div>Get Udemy certificate by completing entire course</div>
<div >
    <button type="button" class="btn btn-outline-secondary disabled no-drop mt-4">Udemy certificate</button>
</div>

</div>
<div></div>

</div>
</div>
<div class="border_tb fnt_1 w-100">
<div class="d-flex justify-content-between p-4">
<div>Features</div>
<div class="d-flex flex-column fnt_1">
<div>Available on <a class="blue">iOS</a> and <a class="blue">Android</a></div>
</div>
<div></div>

</div>
</div>
<Footer/>
</div>

    
</template>
<script>
import Footer from "../components/Footer.vue";
export default {
     components: {
    Footer
}
}
</script>
<style scoped>
.P_4{
    padding: 0 4.8remm;
}
.fnt{
    font-size: 24px;
    font-weight: 700;
    line-height: 1.33em;
}
.fnt_1{
    font-size: 15px;
    /* font-weight:500; */
    line-height: 1.33em;
}
.border_tb{
    border-top: 1px solid rgb(231, 228, 228);
    border-bottom: 1px solid rgb(231, 228, 228);
}
.no-drop{
cursor: no-drop !important;
}
.blue{
     color: #007791;
 }
</style>