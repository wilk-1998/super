<template>
  <div id="app">
    <tab-bar>
      <div class="tab-bar-item">
        <img src="../../assets/img/tabbar/home.svg" alt="" />
        <div>首页</div>
      </div>
      <div class="tab-bar-item">
        <img src="../../assets/img/tabbar/home.svg" alt="" />
        <div>分类</div>
      </div>
      <div class="tab-bar-item">
        <img src="../../assets/img/tabbar/home.svg" alt="" />
        <div>购物车</div>
      </div>
      <div class="tab-bar-item">
        <img src="../../assets/img/tabbar/home.svg" alt="" />
        <div>我的</div>
      </div>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from "./components/tabbar/TabBar.vue";
import TabBarItem from "./components/tabbar/TabBarItem.vue";
export default {
  name:'App'
  components: { TabBar, TabBarItem },
};
</script>

<style>
</style>