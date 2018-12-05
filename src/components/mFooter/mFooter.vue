<template>

 <van-tabbar v-model="active" class="van-hairline--top">
  <van-tabbar-item>
    <span>E号通</span>
    <img
      slot="icon"
      slot-scope="props"
      :src="props.active ? icon.Eactive : icon.Enormal"
    >
  </van-tabbar-item>
  <van-tabbar-item>
    <span>陪护床</span>
    <img
      slot="icon"
      slot-scope="props"
      :src="props.active ? icon.Bactive : icon.Bnormal"
    >
  </van-tabbar-item><van-tabbar-item>
    <span>商城</span>
    <img
      slot="icon"
      slot-scope="props"
      :src="props.active ? icon.Sactive : icon.Snormal"
    >
  </van-tabbar-item><van-tabbar-item>
    <span>我的</span>
    <img
      slot="icon"
      slot-scope="props"
      :src="props.active ? icon.Mactive : icon.Mnormal"
    >
  </van-tabbar-item>
</van-tabbar>
</template>

<script>
import Vue from 'vue'

import { Tabbar, TabbarItem } from 'vant';

Vue.use(Tabbar).use(TabbarItem);
export default {
  data() {
    return {
      active: 0,
      icon: {
        // Enormal: '//Eimg.yzcdn.cn/icon-normal.png',
        // Eactive: '//Eimg.yzcdn.cn/icon-active.png',
        // Bnormal: '//Bimg.yzcdn.cn/icon-normal.png',
        // Bactive: '//Bimg.yzcdn.cn/icon-active.png',
        // Snormal: '//Simg.yzcdn.cn/icon-normal.png',
        // Sactive: '//Simg.yzcdn.cn/icon-active.png',
        // Mnormal: '//Mimg.yzcdn.cn/icon-normal.png',
        // Mactive: '//Mimg.yzcdn.cn/icon-active.png',
      }
    }
  }
}
</script>

<style scoped lang="stylus">
@import '~common/stylus/variable'
@import '~common/stylus/mixin'
</style>
