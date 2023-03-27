<script>
import ThisHeader from './components/ThisHeader.vue'
import ThisMain from './components/ThisMain.vue'
import ThisFooter from './components/ThisFooter.vue'
import ThisFooterBottom from './components/ThisooterBottom.vue'
export default {
  components: {
    ThisHeader,
    ThisMain,
    ThisFooter,
    ThisFooterBottom,
  }
}
</script>

<template>
  <ThisHeader />
  <ThisMain />
  <ThisFooter />
  <ThisFooterBottom />
</template>

<style lang="scss">
@use "./styles/general.scss"
</style>
