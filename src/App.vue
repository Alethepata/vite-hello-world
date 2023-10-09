<script>

import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  name: 'App',
  components:{
    AppTitle,
    AppHero
  }
}
</script>

<template>


  <section>

    <AppTitle/>  

  </section>

  <section class="py-5 mt-3 ">

    <AppHero/>

  </section>

  
</template>

<style>
section:nth-child(2){
  background: linear-gradient(118deg, rgba(9,9,121,1) 0%, rgba(20,71,221,1) 40%, rgba(0,212,255,1) 100%);
  color: white; 
}

</style>
