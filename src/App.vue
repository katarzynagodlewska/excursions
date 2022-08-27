<template>
  <Navbar-el />
</template>

<script>
import NavbarEl from './components/NavbarEl.vue'

export default {
  name: 'App',
  components: {
    NavbarEl
  }
}
</script>

<style lang='scss'>
@import "./styles/main.scss";
</style>
