<template>
  <div id="tab-bar">
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/home.svg" alt="" />
      首页
    </div>
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/home.svg" alt="" />分类
    </div>
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/home.svg" alt="" />购物车
    </div>
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/home.svg" alt="" />我的
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#tab-bar {
  display: flex;
  background-color: #f7f7f7;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  box-shadow: 0 -3px 1px rgba(100, 100, 100, 0.06);
}
.tab-bar-item {
  flex: 1;
  text-align: center;
  height: 49px;
}
</style>