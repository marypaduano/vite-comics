<script>
  import AppHeader from './components/AppHeader.vue'
  import ShowContent from './components/ShowContent.vue'
  import MainApp from './components/MainApp.vue'
  import NavFooter from './components/NavFooter.vue'
  import FooterApp from './components/FooterApp.vue'


export default {
  components: {
    AppHeader,
    ShowContent,
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
    <ShowContent />
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
