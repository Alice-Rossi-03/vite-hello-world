
<script>

  import AppTitle from './components/AppTitle.vue'
  import AppHero from './components/AppHero.vue'


  export default{
    components: {
      AppTitle,
      AppHero 
    }
  }
</script>

<template>
  <AppTitle/>

  <hr> 

  <AppHero/> 
</template>

<style>
  hr{
    opacity: 0.2; 
    margin-block: 1em; 
  }
</style>
