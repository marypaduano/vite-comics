<script>
  import AppHeader from './components/AppHeader.vue'
  import MainContent from './components/MainContent.vue'
  import MainApp from './components/MainApp.vue'
  import NavFooter from './components/NavFooter.vue'
  import FooterApp from './components/FooterApp.vue'


export default {
  components: {
    AppHeader,
    MainContent,
    MainApp,
    NavFooter,
    FooterApp,

  }
}

</script>

<template>
  <header>
    <AppHeader />
  </header>
  <main>
    <MainContent />
    <MainApp />

  </main>
  <footer>
    <NavFooter />
    <FooterApp />

  </footer>
</template>

<style lang="scss">
@use './style/general.scss';
</style>
