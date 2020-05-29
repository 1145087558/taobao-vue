<template>
<div>
  <!-- 首页顶部 -->
  <ShopTop></ShopTop>

</div>

</template>

<script>
import ShopTop from './home/ShopTop'

export default {
  name: "Index",
  components: {
    ShopTop
  }
};
</script>

<style lang="stylus" rel="stylesheet/stylus">
@import '../assets/css/basic/demo.css';
@import '../assets/css/amazeui/amazeui.css';
@import '../assets/css/amazeui/admin.css';
@import '../assets/css/common/hmstyle.css';
</style>