<script>
export default {};
</script>

<template>
  <div class="section">
    <div class="container">
      <div class="card">
        <img
          src="/src/assets/img/buy-comics-digital-comics.png"
          alt="digital comics"
          class="img_2"
        />
        <p>DIGITAL COMICS</p>
      </div>
      <div class="card">
        <img
          src="/src/assets/img/buy-comics-merchandise.png"
          alt="merchandise"
          class="img_1"
        />
        <p>DC MERCHANDISE</p>
      </div>
      <div class="card">
        <img
          src="/src/assets/img/buy-comics-subscriptions.png"
          alt="subscription"
          class="img_1"
        />
        <p>SUBSCRIPTION</p>
      </div>
      <div class="card">
        <img
          src="/src/assets/img/buy-comics-shop-locator.png"
          alt="shop_locator"
          class="img_2"
        />
        <p>COMIC SHOP LOCATOR</p>
      </div>
      <div class="card">
        <img
          src="/src/assets/img/buy-dc-power-visa.svg"
          alt="visa"
          class="img_1"
        />
        <p>DC POWER VISA</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "./../assets/styles/variables.scss" as *;

.section {
  height: 120px;
  background-color: #0c7cec;

  .container {
    @include myContainer;
    display: flex;
    align-items: center;
    justify-content: space-around;

    .card {
      display: flex;
      align-items: center;
      color: white;

      .img_1 {
        width: 70px;
      }

      .img_2 {
        width: 50px;
      }

      p {
        margin-left: 1em;
      }
    }
  }
}
</style>
