<template>
  <div class="shopNav">
    <div class="slideall" style="height: auto;">
      <div class="long-title">
        <span class="all-goods">全部分类</span>
      </div>
      <div class="nav-cont">
        <ul>
          <li class="index">
            <a href="#">首页</a>
          </li>
          <li class="qc">
            <a href="#">闪购</a>
          </li>
          <li class="qc">
            <a href="#">限时抢</a>
          </li>
          <li class="qc">
            <a href="#">团购</a>
          </li>
          <li class="qc last">
            <a href="#">大包装</a>
          </li>
        </ul>
        <div class="nav-extra">
          <i class="am-icon-user-secret am-icon-md nav-user"></i>
          <b></b>我的福利
          <i class="am-icon-angle-right" style="padding-left: 10px;"></i>
        </div>
      </div>
      <!--轮播 -->
      <div class="bannerTwo">
        <div class="am-slider am-slider-default scoll" data-am-flexslider id="demo-slider-0">
          <ul class="am-slides">
            <li class="banner1">
              <a href="introduction.html">
                <img src="../../assets/images/ad5.jpg" />
              </a>
            </li>
            <li class="banner2">
              <a>
                <img src="../../assets/images/ad6.jpg" />
              </a>
            </li>
            <li class="banner3">
              <a>
                <img src="../../assets/images/ad7.jpg" />
              </a>
            </li>
            <li class="banner4">
              <a>
                <img src="../../assets/images/ad8.jpg" />
              </a>
            </li>
          </ul>
        </div>
        <div class="clear"></div>
      </div>
      <!-- 分类左部导航 -->
      <div id="nav" class="navfull" style="position: static;">
        <div class="area clearfix">
          <div class="category-content" id="guide_2">
            <div class="category" style="box-shadow:none ;margin-top: 2px;">
              <ul class="category-list navTwo" id="js_climit_li">
                <li
                  v-for="goods in goodslist"
                  :key="goods.id"
                  @mouseover="lihover(goods.id)"
                  v-show="isList==goods.id"
                >
                  <div class="category-info">
                    <h3 class="category-name b-category-name">
                      <i>
                        <img src="../../assets/images/chocolate.png" />
                      </i>
                      <a class="ml-22" title="巧克力">巧克力</a>
                    </h3>
                    <em>&gt;</em>
                  </div>
                  <div class="menu-item menu-in top">
                    <div class="area-in">
                      <div class="area-bg">
                        <div class="menu-srot">
                          <div class="sort-side">
                            <dl class="dl-sort">
                              <dt>
                                <span title="蛋糕">巧克力</span>
                              </dt>
                              <dd>
                                <a title="蒸蛋糕" href="#">
                                  <span>蒸蛋糕</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="脱水蛋糕" href="#">
                                  <span>脱水蛋糕</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="瑞士卷" href="#">
                                  <span>瑞士卷</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="软面包" href="#">
                                  <span>软面包</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="马卡龙" href="#">
                                  <span>马卡龙</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="千层饼" href="#">
                                  <span>千层饼</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="甜甜圈" href="#">
                                  <span>甜甜圈</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="蒸三明治" href="#">
                                  <span>蒸三明治</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="铜锣烧" href="#">
                                  <span>铜锣烧</span>
                                </a>
                              </dd>
                            </dl>
                            <dl class="dl-sort">
                              <dt>
                                <span title="蛋糕">果冻</span>
                              </dt>
                              <dd>
                                <a title="蒸蛋糕" href="#">
                                  <span>蒸蛋糕</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="脱水蛋糕" href="#">
                                  <span>脱水蛋糕</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="瑞士卷" href="#">
                                  <span>瑞士卷</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="软面包" href="#">
                                  <span>软面包</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="马卡龙" href="#">
                                  <span>马卡龙</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="千层饼" href="#">
                                  <span>千层饼</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="甜甜圈" href="#">
                                  <span>甜甜圈</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="蒸三明治" href="#">
                                  <span>蒸三明治</span>
                                </a>
                              </dd>
                              <dd>
                                <a title="铜锣烧" href="#">
                                  <span>铜锣烧</span>
                                </a>
                              </dd>
                            </dl>
                          </div>
                          <div class="brand-side">
                            <dl class="dl-sort">
                              <dt>
                                <span>实力商家</span>
                              </dt>
                              <dd>
                                <a rel="nofollow" title="花颜巧语 " target="_blank" href="#">
                                  <span class="red">花颜巧语</span>
                                </a>
                              </dd>
                              <dd>
                                <a rel="nofollow" title="糖衣小屋" target="_blank" href="#">
                                  <span>糖衣小屋</span>
                                </a>
                              </dd>
                              <dd>
                                <a rel="nofollow" title="卡拉迪克  " target="_blank" href="#">
                                  <span class="red">卡拉迪克</span>
                                </a>
                              </dd>
                              <dd>
                                <a rel="nofollow" title="暖春童话 " target="_blank" href="#">
                                  <span>暖春童话</span>
                                </a>
                              </dd>
                              <dd>
                                <a rel="nofollow" title="华盛童装批发行 " target="_blank" href="#">
                                  <span>华盛童装批发行</span>
                                </a>
                              </dd>
                              <dd>
                                <a rel="nofollow" title="奈仕华童装旗舰店" target="_blank" href="#">
                                  <span>奈仕华童装旗舰店</span>
                                </a>
                              </dd>
                              <dd>
                                <a rel="nofollow" title="斑蒂尼BONDYNI" target="_blank" href="#">
                                  <span class="red">斑蒂尼BONDYNI</span>
                                </a>
                              </dd>
                              <dd>
                                <a rel="nofollow" title="童衣阁" target="_blank" href="#">
                                  <span class="red">童衣阁</span>
                                </a>
                              </dd>
                            </dl>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <b class="arrow"></b>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <!--小导航 -->
      <div class="am-g am-g-fixed smallnav">
        <div class="am-u-sm-3">
          <a href="sort.html">
            <img src="../../assets/images/navsmall.jpg" />
            <div class="title">商品分类</div>
          </a>
        </div>
        <div class="am-u-sm-3">
          <a href="#">
            <img src="../../assets/images/huismall.jpg" />
            <div class="title">大聚惠</div>
          </a>
        </div>
        <div class="am-u-sm-3">
          <a href="#">
            <img src="../../assets/images/mansmall.jpg" />
            <div class="title">个人中心</div>
          </a>
        </div>
        <div class="am-u-sm-3">
          <a href="#">
            <img src="../../assets/images/moneysmall.jpg" />
            <div class="title">投资理财</div>
          </a>
        </div>
      </div>
      <!--各类活动-->
      <div class="row">
        <li>
          <a>
            <img src="../../assets/images/row1.jpg" />
          </a>
        </li>
        <li>
          <a>
            <img src="../../assets/images/row2.jpg" />
          </a>
        </li>
        <li>
          <a>
            <img src="../../assets/images/row3.jpg" />
          </a>
        </li>
        <li>
          <a>
            <img src="../../assets/images/row4.jpg" />
          </a>
        </li>
      </div>
      <div class="clear"></div>
      <!-- 走马灯 -->
      <div class="marqueenTwo">
        <span class="marqueen-title">
          <i class="am-icon-volume-up am-icon-fw"></i>商城头条
          <em class="am-icon-angle-double-right"></em>
        </span>
        <div class="demo">
          <ul>
            <li class="title-first">
              <a target="_blank" href="#">
                <img src="../../assets/images/TJ2.jpg" />
                <span>[特惠]</span>洋河年末大促，低至两件五折
              </a>
            </li>
            <li class="title-first">
              <a target="_blank" href="#">
                <span>[公告]</span>商城与广州市签署战略合作协议
                <img src="../../assets/images/TJ.jpg" />
                <p>XXXXXXXXXXXXXXXXXX</p>
              </a>
            </li>
            <li>
              <a target="_blank" href="#">
                <span>[特惠]</span>女生节商城爆品1分秒
              </a>
            </li>
            <li>
              <a target="_blank" href="#">
                <span>[公告]</span>华北、华中部分地区配送延迟
              </a>
            </li>
            <li>
              <a target="_blank" href="#">
                <span>[特惠]</span>家电狂欢千亿礼券 买1送1！
              </a>
            </li>
            <li>
              <a target="_blank" href="#">
                <span>[特惠]</span>洋河年末大促，低至两件五折
              </a>
            </li>
            <li>
              <a target="_blank" href="#">
                <span>[公告]</span>华北、华中部分地区配送延迟
              </a>
            </li>
          </ul>
        </div>
      </div>
      <div class="clear"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ShopNav",
  data() {
    return {
      isList: 0,
      goodslist: [{ goodsType: "", id: "" }]
    };
  },
  methods: {
    lihover: function(id) {
      isList = id;
    }
  }
};
</script>

<style>
</style>