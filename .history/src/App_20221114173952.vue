<template>
  <div id="app">
    <tab-bar>
      <tab-bar-item>
        <img slot="item-icon" src="../../assets/img/tabbar/home.svg" alt="" />
        <div>首页</div>
      </tab-bar-item>
      <tab-bar-item>
        <img src="../../assets/img/tabbar/category.svg" alt="" />
        <div>首页</div>
      </tab-bar-item>
      <tab-bar-item>
        <img src="../../assets/img/tabbar/shopcart.svg" alt="" />
        <div>首页</div>
      </tab-bar-item>
      <tab-bar-item>
        <img src="../../assets/img/tabbar/profile.svg" alt="" />
        <div>首页</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from "./components/tabbar/TabBar.vue";
import TabBarItem from "./components/tabbar/TabBarItem.vue";
export default {
  name: "App",
  components: { TabBar, TabBarItem },
};
</script>

<style>
</style>