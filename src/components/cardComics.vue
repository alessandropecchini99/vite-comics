<script>
export default {
  props: {
    urlImg: String,
    titolo: String,
  },
};
</script>

<template>
  <div class="card">
    <img :src="urlImg" :alt="titolo" />
    <h4>{{ titolo }}</h4>
  </div>
</template>

<style lang="scss" scoped>
.card {
  text-align: center;
  width: calc((100% / 6) - 2em);

  img {
    width: 100%;
    object-fit: cover;
    object-position: top;
    aspect-ratio: 1 / 1;
  }

  h4 {
    height: 35px;
  }
}
</style>
