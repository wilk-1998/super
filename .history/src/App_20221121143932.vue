<template>
  <div id="app">
    <router-view></router-view>
    <main-tab-bar />
  </div>
</template>

<script>
import TabBar from "./components/tabbar/TabBar.vue";
import MainTabBar from "./components/mainTabbar/MainTabBar.vue";

export default {
  name: "App",
  components: {
    TabBar,
    MainTabBar,
  },
};
</script>

<style>
@import "./assets/css/base.css";
</style>
