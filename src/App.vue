<template>
  <div id="app">

    <myHeader />
    <myMain />
    <myFooterTop />
    <myFooterCenter />
    <myFooterBottom />
 
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue';
import myMain from './components/myMain.vue';
import myFooterTop from './components/myFooterTop.vue';
import myFooterCenter from './components/myFooterCenter.vue';
import myFooterBottom from './components/myFooterBottom.vue';

export default {
  name: 'App',
  components: {
    myHeader,
    myMain,
    myFooterTop,
    myFooterCenter,
    myFooterBottom

  }
}
</script>

<style lang="scss">
  @import "./assets/style/common.scss";
</style>
