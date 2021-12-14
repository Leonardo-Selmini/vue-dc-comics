<template>
  <section class="flex-row">
    <div class="width-80 flex-row">
      <div class="flex-row">
        <img src="./../../assets/img/buy-comics-digital-comics.png" alt="digital comics icon">
        <span>digital comics</span>
      </div>
      <div class="flex-row">
        <img src="./../../assets/img/buy-comics-merchandise.png" alt="dc merchandise icon">
        <span>dc merchandise</span>
      </div>
      <div class="flex-row">
        <img src="./../../assets/img/buy-comics-subscriptions.png" alt="subsciption icon">
        <span>subscriptions</span>
      </div>
      <div class="flex-row">
        <img src="./../../assets/img/buy-comics-shop-locator.png" alt="shop locator icon">
        <span>shop locator</span>
      </div>
      <div class="flex-row">
        <img src="./../../assets/img/buy-dc-power-visa.svg" alt="dc power visa icon">
        <span>dc power visa</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionStore'
}
</script>

<style lang="scss" scoped>
@import './../../assets/styles/variables.scss';

  section {
    height: 8rem;
    background-color: $lightBlue;
    color: white;
    
    div:nth-of-type(4) img {
      width: 2rem;
    }

    div img {
      width: 3rem;
      margin-right: .5rem;
    }

    div span {
      font-family:Verdana, Geneva, Tahoma, sans-serif;
      font-size: .8rem;
      text-transform: uppercase;
    }
  }

</style>