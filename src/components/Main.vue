<template>
  <main>
    <SectionJumbo/>
  </main>
</template>

<script>
import SectionJumbo from './SectionJumbo.vue';

export default {
  name: 'Main',
  components: {
    SectionJumbo,
  },
}
</script>

<style lang="scss" scoped>
@import './../assets/styles/variables.scss';

  main {
    background-color: $black;
  }
</style>