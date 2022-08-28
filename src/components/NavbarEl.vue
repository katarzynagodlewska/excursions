<template>
  <nav class="nav">
    <div class="nav-lists">
      <ul class="nav-lists__list nav-list-left">
        <img class="logo" src="../assets/logo.png" />
        <li class="nav-list-left__item">
          <router-link :to="{}" class="link"> Home </router-link>
        </li>
        <li class="nav-list-left__item">
          <router-link :to="{}" class="link"> Excursions </router-link>
        </li>
        <li class="nav-list-left__item">
          <router-link :to="{}" class="link"> About us</router-link>
        </li>
        <li class="nav-list-left__item">
          <router-link :to="{}" class="link"> Contact </router-link>
        </li>
      </ul>
      <ul class="nav-lists__list nav-list-right">
        <li class="nav-list-right__item">
          <router-link :to="{}" class="link"
            ><img class="icon-search" src="../assets/search.svg"
          /></router-link>

          <p class="nav-list-right__text">
            <router-link :to="{}" class="link">Search</router-link>
          </p>
        </li>
        <li class="nav-list-right__item">
          <router-link :to="{}" class="link"
            ><img class="icon-cart" src="../assets/shopping-cart.svg"
          /></router-link>

          <p class="nav-list-right__text">
            <router-link :to="{}" class="link">Cart</router-link>
          </p>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavbarEl",
};
</script>

<style lang="scss" scoped>
@import "../styles/modules/navbar.scss";
</style>