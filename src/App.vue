<template>
  <div id="app">
    <header-box/>
    <main-box/>
    <marketing-box/>
    <footer-box/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainBox from './components/MainBox.vue'
import MarketingBox from './components/MarketingBox.vue'
import FooterBox from './components/FooterBox.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
    MarketingBox,
    FooterBox,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

</style>
