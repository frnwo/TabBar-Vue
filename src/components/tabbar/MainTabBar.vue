<template>
<div>
  <tab-bar>
      <!-- 因为"/home"是固定值，不是变量，所以path前面不用加: -->
      <tab-bar-item path="/home" activeColor="blue">
        
        <img class="" slot="item-icon" src="~assets/img/tabbar/home.svg"/>
        <img class="" slot="item-icon-active" src="~assets/img/tabbar/home_active.svg"/>
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="blue">
        <img class="" slot="item-icon" src="~assets/img/tabbar/category.svg"/>
         <img class="" slot="item-icon-active" src="~assets/img/tabbar/category_active.svg"/>
        <div  slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="blue">
        <img class="" slot="item-icon" src="~assets/img/tabbar/cart.svg"/>
         <img class="" slot="item-icon-active" src="~assets/img/tabbar/cart_active.svg"/>
        <div  slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="blue">
        <img class="" slot="item-icon" src="~assets/img/tabbar/profile.svg"/>
         <img class="" slot="item-icon-active" src="~assets/img/tabbar/profile_active.svg"/>
        <div  slot="item-text">我的</div>
      </tab-bar-item>
      
    </tab-bar>
</div>
</template>

<script>
import TabBar from './TabBar';
import TabBarItem from './TabBarItem';

export default {
  components:{
    TabBar,
    TabBarItem,
  }
}
</script>

<style>

</style>