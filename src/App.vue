<template>
  <div id="app">
    <!-- 路由的出口 -->
    <router-view />
    <i class="toutiao toutiao-shoucang"></i>
    <van-cell title="单元格" is-link />
    <van-cell title="单元格" is-link value="内容" />
    <van-cell title="单元格" is-link arrow-direction="down" value="内容" />
    <van-button loading type="primary" />
    <van-button loading type="primary" loading-type="spinner" />
    <van-button loading type="info" loading-text="加载中..." />
  </div>
</template>
<script>
export default {}
</script>
<style lang="less">
</style>
