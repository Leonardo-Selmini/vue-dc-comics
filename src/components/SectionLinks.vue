<template>
  <section>
    <div class="width-80 space-between">
      <div class="flex">
        <div class="column">
          <ul>
            <li>
              <h2>dc comics</h2>
            </li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <ul>
            <li>
              <h2>shop</h2>
            </li>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
        <div class="column">
          <ul>
            <li>
              <h2>dc</h2>
            </li>
            <li>Term Of Use</li>
            <li>Privacy Policy (New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Concact Us</li>
          </ul>
        </div>
        <div class="column">
          <ul>
            <li>
              <h2>sites</h2>
            </li>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>
      <img src="./../assets/img/dc-logo-bg.png" alt="dc logo footer">
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionLinks'
}
</script>

<style lang="scss" scoped>
@import './../assets/styles/variables.scss';

  section {
    position: relative;
    height: 25rem;
    font-size: .8rem;
    background-image: url("./../assets/img/footer-bg.jpg");
    color: $lightGrey;
    overflow-y: hidden;

    .flex {
      display: flex;
      
      .column {
        padding: 1.6rem;

        ul li {
          line-height: 1.6rem;
          font-family: Arial, Helvetica, sans-serif;
          list-style: none;

          h2 {
            text-transform: uppercase;
            color: white;
            padding: 1rem 0 .4rem;
          }
        }
      }
    }

    img{
      position: absolute;
      right: 5rem;
      top: -6rem;
    }
  }
</style>