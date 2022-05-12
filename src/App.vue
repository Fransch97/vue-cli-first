<template>
  <div id="app">
    <ComHeader msg="Ciao il sono il header" />
    <MyHero/>
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
