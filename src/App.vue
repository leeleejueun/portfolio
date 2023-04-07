<template>
  <div id="app">
    <MenuComp />
    <router-view/>
  </div>
</template>

<script>
import MenuComp from './components/MenuComp.vue';

export default {
  name: 'App',
  components:{
    MenuComp
  }
}
</script>

<style lang="scss">
@import './assets/css/common.scss';
@import './assets/css/reset.css';
</style>
