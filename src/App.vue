<template>
  <div id="app">
    <header-box />
    <jumbo-main />
    <main-cards />
    <footer-nav />
    <footer-app />
    <footer-sign-up />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import JumboMain from './components/JumboMain.vue'
import MainCards from './components/MainCards.vue'
import FooterNav from './components/FooterNav.vue'
import FooterApp from './components/FooterApp.vue'
import FooterSignUp from './components/FooterSignUp.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    JumboMain,
    MainCards,
    FooterNav,
    FooterApp,
    FooterSignUp
  }
}
</script>

<style lang="scss">
@import './style/main.scss'
</style>
