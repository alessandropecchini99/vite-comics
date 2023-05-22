<script>
export default {
  props: {
    menuVoice: String,
  },
};
</script>

<template>
  <li>{{ menuVoice }}</li>
</template>

<style lang="scss" scoped>
$DC_colore: #0c7cec;
li {
  display: flex;
  align-items: center;

  &:hover {
    color: $DC_colore;
    border-bottom: 5px $DC_colore solid;
    cursor: pointer;
  }
}
</style>
