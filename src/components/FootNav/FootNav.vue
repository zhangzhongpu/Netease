<template>
  <mt-tabbar >
    <mt-tab-item id="首页">
      <div>1223</div>
      分类
    </mt-tab-item>
    <mt-tab-item id="分类">
      <img slot="icon" src="../../assets/100x100.png">
      分类
    </mt-tab-item>
    <mt-tab-item id="识物">
      <img slot="icon" src="../../assets/100x100.png">
      识物
    </mt-tab-item>
    <mt-tab-item id="购物车">
      <img slot="icon" src="../../assets/100x100.png">
      购物车
    </mt-tab-item>
    <mt-tab-item id="个人">
      <img slot="icon" src="../../assets/100x100.png">
      个人
    </mt-tab-item>
  </mt-tabbar>
</template>

<script>
  import Vue from 'vue'
  import { Tabbar, TabItem } from 'mint-ui';

  Vue.component(Tabbar.name, Tabbar);
  Vue.component(TabItem.name, TabItem);
export default {
  name: 'FootNav'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
