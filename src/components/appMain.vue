<script>
export default {};
</script>

<template>
  <div class="sezione_1">
    <div class="container_1">
      <h1>>>> Content goes here&lt;&lt;&lt;</h1>
    </div>
  </div>
  <div class="sezione_2">
    <div class="container_2">
      <div class="card">
        <img
          src="/public/img/buy-comics-digital-comics.png"
          alt="digital comics"
          class="img_2"
        />
        <p>DIGITAL COMICS</p>
      </div>
      <div class="card">
        <img
          src="/public/img/buy-comics-merchandise.png"
          alt="merchandise"
          class="img_1"
        />
        <p>DC MERCHANDISE</p>
      </div>
      <div class="card">
        <img
          src="/public/img/buy-comics-subscriptions.png"
          alt="subscription"
          class="img_1"
        />
        <p>SUBSCRIPTION</p>
      </div>
      <div class="card">
        <img
          src="/public/img/buy-comics-shop-locator.png"
          alt="shop_locator"
          class="img_2"
        />
        <p>COMIC SHOP LOCATOR</p>
      </div>
      <div class="card">
        <img src="/public/img/buy-dc-power-visa.svg" alt="visa" class="img_1" />
        <p>DC POWER VISA</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.sezione_1 {
  height: 35vh;
  background-color: #1c1c1c;
  position: relative;
  z-index: 100;
  .container_1 {
    width: 80%;
    height: 100%;
    margin-inline: auto;
    display: flex;
    align-items: center;
    color: white;
  }
}
.sezione_2 {
  height: 15vh;
  background-color: #0582f9;

  .container_2 {
    width: 80%;
    height: 100%;
    margin-inline: auto;
    display: flex;
    align-items: center;
    justify-content: space-around;

    .card {
      display: flex;
      align-items: center;
      color: white;

      .img_1 {
        width: 90px;
      }

      .img_2 {
        width: 70px;
      }

      p {
        margin-left: 1em;
      }
    }
  }
}
</style>
