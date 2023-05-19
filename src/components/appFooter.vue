<script>
export default {};
</script>

<template>
  <div class="sezione_1">
    <div class="container_1">
      <div class="colonne">
        <div class="colonna">
          <ul>
            <li><h2>DC COMICS</h2></li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>

          <ul>
            <li><h2>SHOP</h2></li>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>

        <div>
          <ul>
            <li><h2>DC</h2></li>
            <li>Terms Of Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choice</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>

        <div>
          <ul>
            <li><h2>SITES</h2></li>
            <li>DC</li>
            <li>MAD Megazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
        <img src="/public/img/dc-logo-bg.png" alt="logo" />
      </div>
    </div>
  </div>
  <div class="sezione_2">
    <div class="container_2">
      <button><h2>SIGN-UP NOW!</h2></button>
      <div class="icon">
        <h2>FOLLOW US</h2>
        <img src="/public/img/footer-facebook.png" alt="facebook" />
        <img src="/public/img/footer-twitter.png" alt="twitter" />
        <img src="/public/img/footer-youtube.png" alt="youtube" />
        <img src="/public/img/footer-pinterest.png" alt="pinterest" />
        <img src="/public/img/footer-periscope.png" alt="periscope" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.sezione_1 {
  background-image: url(/public/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  height: 30vh;

  .container_1 {
    height: 100%;
    width: 80%;
    margin-inline: auto;
    position: relative;
    display: flex;
    align-items: center;

    .colonne {
      width: 100%;
      display: flex;
      color: grey;
      font-size: 0.85em;
      font-weight: 300;

      ul {
        list-style-type: none;
        margin-right: 4.5em;
      }

      li {
        margin-bottom: 0.5em;
        &:hover {
          color: white;
          cursor: pointer;
        }
      }

      h2 {
        margin-bottom: 0.5em;
        color: white;
        font-size: 2em;
      }

      img {
        z-index: 0;
        position: absolute;
        right: 135px;
        top: -90px;
      }

      .colonna {
        ul {
          margin-bottom: 1em;
        }
      }
    }
  }
}
.sezione_2 {
  height: 10vh;
  background-color: #303030;
  position: relative;
  z-index: 100;

  .container_2 {
    height: 100%;
    width: 80%;
    margin-inline: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    button {
      background-color: #303030;
      color: white;
      padding: 10px;
      border: 2px solid #1f6cc4;
      &:hover {
        background-color: #003c80;
        cursor: pointer;
      }
    }

    .icon {
      display: flex;
      align-items: center;
      gap: 1em;

      h2 {
        color: #258bff;
        margin-right: 0.5em;
      }
    }
  }
}
</style>
