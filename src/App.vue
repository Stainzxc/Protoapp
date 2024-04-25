<template>
  <div class="container">
    <Header />
    <Home />
    <About />
    <Advertise />
    <Action />
    <Footer />
    <img src="@/assets/images/bg-decals.svg" alt="" class="container__bg-decals" />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Advertise from './components/Advertise.vue'
import Action from './components/Action.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Home,
    About,
    Advertise,
    Action,
    Footer
  }
}
</script>

<style lang="scss" scoped>
/* @media (min-width: 1024px) {
  header {
    display: flex;
    padding-right: calc(var(--section-gap) / 2);
  }
} */
// @import './assets/style.scss'
</style>
