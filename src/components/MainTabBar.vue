<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <img slot="item-icon" src="@assets/img/home.svg" alt="">
      <img slot="item-icon-active" src="@assets/img/home-a.svg" alt="">
      <div slot="item-text">首頁</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="blue">
      <img slot="item-icon" src="@assets/img/category.svg" alt="">
      <img slot="item-icon-active" src="@assets/img/category-a.svg" alt="">
      <div slot="item-text">分類</div>
    </tab-bar-item>
    <tab-bar-item path="/message" activeColor="blue">
      <img slot="item-icon" src="@assets/img/message.svg" alt="">
      <img slot="item-icon-active" src="@assets/img/message-a.svg" alt="">
      <div slot="item-text">訊息</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="blue">
      <img slot="item-icon" src="@assets/img/person.svg" alt="">
      <img slot="item-icon-active" src="@assets/img/person-a.svg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "@/components/tabbar/TabBar"
  import TabBarItem from "@/components/tabbar/TabBarItem"

  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>