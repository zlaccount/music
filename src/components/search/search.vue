<template>
  <div>
      
      <div class="van-hairline--top"></div>
      <van-loading color="black" />
      <van-loading color="white" />
      <van-loading type="spinner" color="black" />
      <van-loading type="spinner" color="white" />
  </div>
</template>

<script type="text/ecmascript-6">
import Vue from 'vue'

import { Loading  } from 'vant';
import { Button } from 'vant';

Vue.use(Button);
export default {
    components: {  
     [Loading.name]: Loading
  },
  data() {
    return {
    }
}
}
</script>

<style scoped lang="stylus">
</style>
