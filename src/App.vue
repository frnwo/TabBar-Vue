<template>
  <div id="app">
    <router-view/>
    <main-tab-bar></main-tab-bar>
  </div>
</template>
<script>
import MainTabBar from './components/tabbar/MainTabBar';

export default {
  name:'App',
  components:{
    MainTabBar,
   
  }
}
</script>
   

<style>
/* 在style引用css前面需要加@ ，在js文件里就直接 import  */
    @import "./assets/css/base.css";

</style>
