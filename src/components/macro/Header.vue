<template>
  <header>
    <div class="space-between width-80">
      <img src="../../assets/img/dc-logo.png" alt="DC Logo">
      <Navbar/>
    </div>
  </header>
</template>

// 0000000- SCRIPT -00000000
<script>
// --import--
import Navbar from '../sections/Navbar.vue'
//-- export --
export default {
  name: 'Header',
  components: {
    Navbar,
  }
}
</script>

// 00000000- SCRIPT -000000000
<style lang="scss" scoped>
  header {
    background-color: white;
  }

  div.space-between {
    height: 7rem;

    img {
      height: 5rem;
    }
  }
</style>