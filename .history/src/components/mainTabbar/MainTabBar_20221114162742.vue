<template>
  <div id="#app">
    <router-view></router-view>
    <main-tab-bar />
  </div>
</template>

<script>
import MainTabBar from "@/components/mainTabbar";

export default {
  name: "MainTabBar",
  components: {
    MainTabBar,
  },
};
</script>

<style scoped>
</style>
