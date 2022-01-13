<template>
  <div id="app">
    <Header />
    <Jumbo />
    <Jumbonav />
    <Footer />
    <SubFooter />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import Jumbonav from './components/Jumbonav.vue'
import Footer from './components/Footer.vue'
import SubFooter from './components/SubFooter.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Jumbonav,
    Footer,
    SubFooter
  }
}
</script>

<style lang="scss">
@import "./assets/scss/style.scss"

</style>
