<script>
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooterTop from './components/AppFooterTop.vue';
  import AppFooterMiddle from './components/AppFooterMiddle.vue';
  import AppFooterBottom from './components/AppFooterBottom.vue';
  

  export default {
    components:{
      AppHeader,
      AppMain,
      AppFooterTop,
      AppFooterMiddle,
      AppFooterBottom
    }
  }
</script>

<template>
  
    <AppHeader></AppHeader>
    <AppMain></AppMain>
    <AppFooterTop></AppFooterTop>
    <AppFooterMiddle></AppFooterMiddle>
    <AppFooterBottom></AppFooterBottom>
  
</template>

<style lang="scss" scoped>

</style>
