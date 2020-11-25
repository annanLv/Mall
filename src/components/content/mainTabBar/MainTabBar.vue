<template>
  <TabBar>
    <TabBarItem path="/home">
      <img slot="item-icon" src="~assets/img/tabbar/home.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/home_active.svg" alt="">
      <span slot="item-text">首页</span>
    </TabBarItem>
    <TabBarItem path="/category">
      <img slot="item-icon" src="~assets/img/tabbar/category.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/category_active.svg" alt="">
      <span slot="item-text">分类</span>
    </TabBarItem>
    <TabBarItem path="/cart">
      <img slot="item-icon" src="~assets/img/tabbar/cart.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/cart_active.svg" alt="">
      <span slot="item-text">购物车</span>
    </TabBarItem>
    <TabBarItem path="/profile">
      <img slot="item-icon" src="~assets/img/tabbar/profile.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/profile_active.svg" alt="">
      <span slot="item-text">我的</span>
    </TabBarItem>
  </TabBar>
</template>

<script>
  import TabBar from "@/components/common/tabBar/TabBar";
  import TabBarItem from "@/components/common/tabBar/TabBarItem";

  export default {
    name: "MainTabBar",
    components: {
      TabBar, TabBarItem
    }
  }
</script>

<style scoped>

</style>
