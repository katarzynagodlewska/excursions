<template>
  <section class="slide">
    <div class="slide__content">
      <h1 class="slide__title">
        Popular and spectacular <span class="slide__title--black-background">Seljalandsfoss</span> waterfall
      </h1>
      <p class="slide__description">
        Amazing waterfall has its origins underneath the glacier
        <span class="slide__description--bold">Eyjafjallajökull</span> and pathway that stretches around it
      </p>
      <button class="slide__button">Read more</button>
    </div>
    <img src="../assets/waterfall.png" class="slide__img" />
  </section>
</template>

<script>
export default {
  name: "SlideItemWaterfall"
}
</script>

<style lang="scss">
@import '../styles/modules/slide.scss';
</style>