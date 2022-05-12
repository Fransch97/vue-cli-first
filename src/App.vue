<template>
  <div id="app">
    <ComHeader msg="Zoidbergs Stroy's " />
    <MyHero left="ogni Ven" right="alle 15:30" />
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
