<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
    <router-view></router-view>
    </keep-alive>
    <m-footer></m-footer>
  </div>
</template>

<script type="text/ecmascript-6">
import MHeader from 'components/mheader/mheader'
import MFooter from 'components/mfooter/mfooter'
import Tab from 'components/tab/index'
export default {
  data() {
    return {

    }
  },
  components: {
    MHeader,
    MFooter,
    Tab
  }
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>
