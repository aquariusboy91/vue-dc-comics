<template>
  <div id="app">
    <Header />
    <Jumbo />
    <Jumbonav />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import Jumbonav from './components/Jumbonav.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Jumbonav,
    Footer
  }
}
</script>

<style lang="scss">
@import "./assets/scss/style.scss"

</style>
