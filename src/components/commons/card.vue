<template>
  <div>
    <img :src="prop.thumb" :alt="prop.type">
    <h4>{{prop.series}}</h4>
  </div>
</template>

<script>
export default {
  name: 'card',
  props: {
    prop: Object,
  }
}
</script>

<style lang="scss" scoped>
  h4 {
    text-align: center;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif ;
    text-transform: uppercase;
    color: white;
    margin-top: .5rem;
  }
</style>