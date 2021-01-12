<template>
    <div>
        <div class="header_search pt-5">
            <div class="w-50">
                
<input type="text" placeholder="Search all course questions" class="search" /></div>
<div  class="searchicon"><img src="../assets/search copy.svg"/></div>
        </div>
<div class="d-flex justify-content-center">
<div>
    <button class="btn btn-secondary btn-lg dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    All lectures
  </button></div>
  <div>
    <button class="btn btn-secondary btn-lg dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Sort by most recent
  </button></div>
  <div>
    <button class="btn btn-secondary btn-lg dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Filter questions
  </button></div>
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
*{
    font-family: sf pro display,-apple-system,BlinkMacSystemFont,Roboto,segoe ui,Helvetica,Arial,sans-serif,apple color emoji,segoe ui emoji,segoe ui symbol;
}
.header_search{
display: flex;
flex: 1;
justify-content: center;

    font-size: 24px;
    font-weight: 700;
    line-height: 1.33em;
}
.search{
   border-color: #fff;
    display: block;
    width: 100%;
    height: 44px;
    /* padding: 10px 12px; */
    font-size: 16px;
    line-height: 1.43;
    color: #29303b;
    background-color: #fff;
    background-image: none;
    border: 1px solid #8a92a3;
    border-radius: 2px;
    box-shadow: none;
    transition: border-color ease-in-out .08s,box-shadow ease-in-out .08s;
}

.searchicon{
    background-color: #007791;
    padding: 7px;
    /* height: 31px !important; */
    align-self: center;
}
.search-results {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
}
</style>