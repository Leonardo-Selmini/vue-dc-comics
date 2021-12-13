<template>
  <nav>
    <ul class="flex-row">
      <li v-for="(link, index) in links" :key="index" class="flex-row">
        <a href="#">{{link.text}}</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  data() {
    return {
      links: [
        {
          text: 'characters',
          active: false
        },
        {
          text: 'comics',
          active: false
        },
        {
          text: 'movies',
          active: false
        },
        {
          text: 'tv',
          active: false
        },
        {
          text: 'games',
          active: false
        },
        {
          text: 'collectibles',
          active: false
        },
        {
          text: 'videos',
          active: false
        },
        {
          text: 'fans',
          active: false
        },
        {
          text: 'news',
          active: false
        },
        {
          text: 'shop',
          active: false
        }
      ]
    }
  }
}
</script>

<style lang='scss' scoped>
@import './../assets/styles/variables.scss';
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300;400;700&display=swap');

  ul {
    list-style: none;

    li {
      padding: 0 1rem;

      a {
        font-family: 'Arial Narrow', Arial, sans-serif;
        font-weight: bolder;
        color: $grey;
        text-transform: uppercase;
        text-decoration: none;
        padding: calc((7rem - 2rem) / 2) 0;
        border-top: 5px solid white;
        border-bottom: 5px solid white;
        transition : border 500ms ease-out;

        &:hover {
          color: $lightBlue;
          border-bottom: 5px solid $lightBlue;
        }
      }
    }
  }

</style>