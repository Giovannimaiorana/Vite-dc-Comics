<script>
import ThisHeader from './components/ThisHeader.vue'
import ThisMain from './components/ThisMain.vue'
import ThisFooter from './components/ThisFooter.vue'
import ThisFooterBottom from './components/ThisooterBottom.vue'
import ThisMainJumbo from './components/ThisMainJumbo.vue'
export default {
  components: {
    ThisHeader,
    ThisMain,
    ThisFooter,
    ThisFooterBottom,
    ThisMainJumbo,
  }
}
</script>

<template>
  <header>
    <ThisHeader />
  </header>


  <main>
    <ThisMainJumbo />
    <ThisMain />
  </main>

  <footer>
    <ThisFooter />
    <ThisFooterBottom />
  </footer>
</template>

<style lang="scss">
@use "./styles/general.scss"
</style>
