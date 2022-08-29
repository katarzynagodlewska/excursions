<template>
  <Navbar-el />
  <main>
    <router-view />
  </main>
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
