<template>
  <footer>
    <SectionLinks/>
    <SectionSocial/>
  </footer>
</template>

<script>
// --import--
import SectionLinks from '../sections/SectionLinks.vue';
import SectionSocial from '../sections/SectionSocial.vue';

// --export--
export default {
  name: 'Footer',
  components: {
    SectionLinks,
    SectionSocial
  }
}
</script>

<style>

</style>