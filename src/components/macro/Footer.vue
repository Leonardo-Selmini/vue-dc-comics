<template>
  <footer>
    <SectionStore/>
    <SectionLinks/>
    <SectionSocial/>
  </footer>
</template>

<script>
// --import--
import SectionStore from '../sections/SectionStore.vue'
import SectionLinks from '../sections/SectionLinks.vue';
import SectionSocial from '../sections/SectionSocial.vue';

// --export--
export default {
  name: 'Footer',
  components: {
    SectionStore,
    SectionLinks,
    SectionSocial
  }
}
</script>

<style>

</style>