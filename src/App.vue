<template>
  <div id="app">
    <body>
      <Header/>
      <Main/>
      <SectionStore/>
    </body>
  </div>
</template>

//00000000- SCRIPT -00000000
<script>
//--import--
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import SectionStore from './components/SectionStore.vue';

//--export--
export default {
  name: 'App',
  components: {
    Header,
    Main,
    SectionStore
  }
}
</script>

//00000000- STYLE -0000000
<style lang="scss">
@import './assets/styles/variables.scss';

//--commons--
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.flex-row {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

.space-between {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.width-80 {
  width: 80%;
  margin: 0 auto;
}

</style>
