<template>
  <div id="app">
    <header-box />
    <jumbo-main />
    <main-cards />
    <!-- <footer-app /> -->
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumboMain from './components/JumboMain.vue'
import MainCards from './components/MainCards.vue'
// import FooterApp from './components/FooterApp.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboMain,
    MainCards,
    // FooterApp
  }
}
</script>

<style lang="scss">
@import './style/main.scss'
</style>
