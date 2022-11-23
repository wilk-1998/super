<template>
  <div id="tab-bar">
    <div class="tab-bar-item">首页</div>
    <div class="tab-bar-item">分类</div>
    <div class="tab-bar-item">购物车</div>
    <div class="tab-bar-item">我的</div>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import "./assets/css/base.css";
#tab-bar {
  display: flex;
  background-color: #f7f7f7;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
}
.tab-bar-item {
  flex: 1;
  text-align: center;
  height: 49px;
}
</style>