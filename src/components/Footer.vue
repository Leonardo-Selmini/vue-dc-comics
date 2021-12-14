<template>
  <footer>
    <SectionLinks/>
    <SectionSocial/>
  </footer>
</template>

<script>
// --import--
import SectionLinks from './SectionLinks.vue';
import SectionSocial from './SectionSocial.vue';

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