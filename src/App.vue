<template>
  <div id="app">
   <Navigation/> 
   <Content/>
  
</div>
</template>

<script>
import Navigation from './components/Navigation.vue';
import Content from './components/Content.vue';


export default {
  name: 'app',
  components: {
    Navigation,
    Content,
    
    
  },
  data() {
    return {
  }
  },
  methods: {
    
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css?family=Lato:400,700');

  body {
    background: #EEF1F4 !important;
    
  margin: 0;
 }
*{
  font-family: sf pro text,-apple-system,BlinkMacSystemFont,Roboto,segoe ui,Helvetica,Arial,sans-serif,apple color emoji,segoe ui emoji,segoe ui symbol;

}
</style>
