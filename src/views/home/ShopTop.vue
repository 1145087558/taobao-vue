<template>

<div class="hmtop">
 <!--顶部导航条 -->
  <Header></Header>
  <!--悬浮搜索框-->
  <PSearch></PSearch>
  <div class="clear"></div>
  <!--商品分类-->
  <ShopNav></ShopNav>
</div>

  
</template>


<script>
import Header from "../../components/Header";
import PSearch from "../../components/Search";
import ShopNav from "./ShopNav"

export default {
name: "ShopTop",
components: {
    Header,
    PSearch,
    ShopNav
  }
}
</script>