<template>
  <tab-bar>
    <tab-bar-item link="/home" activeColor="#d81e06">
      <img src="~assets/img/tabbar/home.svg" alt="" slot="item-icon" />
      <img
        src="~assets/img/tabbar/home_active.svg"
        alt=""
        slot="item-icon-active"
      />
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item link="/category" activeColor="#d81e06">
      <img src="~assets/img/tabbar/category.svg" alt="" slot="item-icon" />
      <img
        src="~assets/img/tabbar/category_active.svg"
        alt=""
        slot="item-icon-active"
      />
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item link="/cart" activeColor="#d81e06">
      <img src="~assets/img/tabbar/shopcart.svg" alt="" slot="item-icon" />
      <img
        src="~assets/img/tabbar/shopcart_active.svg"
        alt=""
        slot="item-icon-active"
      />
      <div slot="item-text">购物</div>
    </tab-bar-item>
    <tab-bar-item link="/profile" activeColor="#d81e06">
      <img src="~assets/img/tabbar/profile.svg" alt="" slot="item-icon" />
      <img
        src="~assets/img/tabbar/profile_active.svg"
        alt=""
        slot="item-icon-active"
      />
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
import TabBar from "components/common/tabbar/TabBar.vue";
import TabBarItem from "components/common/tabbar/TabBarItem.vue";

export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem,
  },
};
</script>

<style>
</style>
