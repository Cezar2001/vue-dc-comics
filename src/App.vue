<template>
  <div id="app">
    <header-box :nav="nav"/>
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
  },
  data() {
    return {
      nav: [
        {
        id: '1',
        label: 'CHARACTERS',
        url: '/CHARACTERS'
        },
        {
          id: '2',
          label: 'COMICS',
          url: '/COMICS'
        },
        {
          id: '3',
          label: 'MOVIES',
          url: '/MOVIES'
        },
        {
          id: '4',
          label: 'TV',
          url: '/TV'
        },
        {
          id: '5',
          label: 'GAMES',
          url: '/GAMES'
        },
        {
          id: '6',
          label: 'COLLECTIBLES',
          url: '/COLLECTIBLES'
        },
        {
          id: '7',
          label: 'VIDEOS',
          url: '/VIDEOS'
        },
        {
          id: '8',
          label: 'FANS',
          url: '/FANS'
        },
        {
          id: '9',
          label: 'NEWS',
          url: '/NEWS'
        },
        {
          id: '10',
          label: 'SHOP',
          url: '/SHOP'
        },
      ]
    }
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import './style/main.scss';
</style>
