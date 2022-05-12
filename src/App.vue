<template>
  <div id="app">
    <ComHeader msg="Ciao il sono il header" />
    <MyHero msg="Jumbotron"/>
  </div>
</template>




<script>
import ComHeader from '@/components/ComHeader.vue'
import MyHero from '@/components/MyHero.vue'
export default {
  components: {
    ComHeader,
    MyHero
  }
  
}
</script>





<style lang="scss">
// #app {
  
// }
</style>
