<template>
  <main>
    <SectionJumbo/>
    <SectionSeries/>
  </main>
</template>

<script>
import SectionJumbo from '../sections/SectionJumbo.vue';
import SectionSeries from '../sections/SectionSeries.vue';

export default {
  name: 'Main',
  components: {
    SectionJumbo,
    SectionSeries,
  },
}
</script>

<style lang="scss" scoped>
@import './../../assets/styles/variables.scss';

  main {
    background-color: $black;
  }
</style>