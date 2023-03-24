<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterMiddle from './components/AppFooterMiddle.vue';
import AppFooterBottom from './components/AppFooterBottom.vue';
import AppJumbo from './components/AppJumbo.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooterTop,
    AppFooterMiddle,
    AppFooterBottom,
    AppJumbo
  }
}
</script>

<template>
  <header>
    <AppHeader></AppHeader>
  </header>

  <AppJumbo></AppJumbo>
  
  <AppMain></AppMain>

  <footer>
    <AppFooterTop></AppFooterTop>
    <AppFooterMiddle></AppFooterMiddle>
    <AppFooterBottom></AppFooterBottom>
  </footer>
  
</template>

<style lang="scss" scoped></style>
