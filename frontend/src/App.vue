<template>
  <div id="app">
    <headertop></headertop>
    <footerbottom></footerbottom>
    <div id="nav">
       <!--<router-link to="/">Home</router-link> 
       <router-link to="/about">About</router-link>-->
    </div>
    <router-view/>
  </div>
</template>

<script>
import headertop from '@/components/headertop.vue'
import footerbottom from '@/components/footerbottom.vue'

export default {
  name: 'app',
  components: {
    headertop,
    footerbottom
  }
}

</script>

<style lang="scss" scoped>

</style>

