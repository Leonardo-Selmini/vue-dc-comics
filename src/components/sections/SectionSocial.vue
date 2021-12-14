<template>
  <section>
    <div class="width-80 space-between">
      <a href="#">SIGN UP NOW</a>
      <div class="social-container flex-row">
        <span>follow us</span>
        <img src="./../../assets/img/footer-facebook.png" alt="facebook logo">
        <img src="./../../assets/img/footer-twitter.png" alt="twitter logo">
        <img src="./../../assets/img/footer-youtube.png" alt="youtube logo">
        <img src="./../../assets/img/footer-pinterest.png" alt="pinterest logo">
        <img src="./../../assets/img/footer-periscope.png" alt="periscope logo">
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionSocial'
}
</script>

<style lang="scss" scoped>
@import './../../assets/styles/variables.scss';

section {
  background-color: $darkGrey;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;

  div.space-between {
    height: 7rem;

    a {
      text-decoration: none;
      color: white;
      padding: .6rem 1rem;
      border: 2px solid $lightBlue;
    }

    div span {
      text-transform: uppercase;
      color: $lightBlue;
      margin-right: .6rem;
    }

    div img {
      margin: 0 .4rem;
    }
  }
}

</style>