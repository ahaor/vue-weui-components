<template>
  <weui-tab id="app">
    <weui-tab-panel>
      <weui-transition-fade>
        <router-view></router-view>
      </weui-transition-fade>
    </weui-tab-panel>
    <tabbar></tabbar>
  </weui-tab>
</template>

<script>
import Tabbar from './components/Tabbar'
export default {
  name: 'app',
  components: {
    Tabbar,
  },
}
</script>

<style type="text/css" lang="scss">
html, body {
  height: 100%;
}
</style>