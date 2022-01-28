<template>
  <div id="app">
    <header-box :buttons="nav"/>
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
  },
  data () {
    return {
      nav:[
        {
          name:'CHARACTERS',
          id:'zSuMOLPVCN'
        },
        {
          name:'COMICS',
          id:'MV5AYz3ifU'
        },
        {
          name:'MOVIES',
          id:'O9wOrpZuBa'
        },
        {
          name:'TV',
          id:'xWrmKxn2PY'
        },
        {
          name:'GAMES',
          id:'mzo6ppIKEU'
        },
        {
          name:'COLLECTIBLES',
          id:'4ez7ptxqk5'
        },
        {
          name:'VIDEOS',
          id:'M2NAQfJ6al'
        },
        {
          name:'FANS',
          id:'8tB4kR9JPX'
        },
        {
          name:'NEWS',
          id:'HfNR5anUYB'
        },
        {
          name:'SHOP',
          id:'1BXScQiH07'
        },
       
      ]
    }
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

</style>
