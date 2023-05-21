<script>
export default {};
</script>

<template>
  <div class="section">
    <div class="container">
      <div class="card-group">
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>

        <!-- .---------- -->
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <div class="card">
          <img
            src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
            alt="prova"
          />
          <h2>titolone</h2>
        </div>
        <!-- ......... -->
      </div>

      <div class="btn">
        <button>LEARN MORE</button>
      </div>

      <div class="label">
        <h1>CURRENT SERIES</h1>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "./../assets/styles/variables.scss" as *;

.section {
  height: fit-content;
  background-color: #1c1c1c;
  z-index: 100;

  .container {
    @include myContainer;
    color: white;
    padding-top: 4em;
    position: relative;

    .card-group {
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2em;

      .card {
        text-align: center;
        width: calc((100% / 6) - 2em);

        img {
          width: 100%;
        }
      }
    }

    .btn {
      width: 100%;
      display: flex;
      justify-content: center;
      padding-top: 3em;
      padding-bottom: 1em;

      button {
        background-color: #0c7cec;
        color: white;
        border: 0;
        padding: 10px 45px;
        &:hover {
          background-color: #0056a7;
        }
      }
    }

    .label {
      background-color: #0c7cec;
      padding: 0.5em;
      position: absolute;
      top: -1.5em;
    }
  }
}
</style>
