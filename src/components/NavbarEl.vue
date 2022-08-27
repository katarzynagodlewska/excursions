<template>
  <nav class="nav">
    <div class="nav-lists">
      <ul class="nav-lists__list nav-list-left">
        <img class="logo" src="../assets/logo.png" />
        <li class="nav-list-left__item">Home</li>
        <li class="nav-list-left__item">Excursions</li>
        <li class="nav-list-left__item">About us</li>
        <li class="nav-list-left__item">Contact</li>
      </ul>
      <ul class="nav-lists__list nav-list-right">
        <li class="nav-list-right__item">
          <img class="icon-search" src="../assets/search.svg"/>
          <p class="nav-list-right__text">Search</p>
        </li>
        <li class="nav-list-right__item">
          <img class="icon-cart" src="../assets/shopping-cart.svg"/>
          <p class="nav-list-right__text">Cart</p>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
name: "NavbarEl"
}
</script>

<style lang="scss" scoped>
</style>