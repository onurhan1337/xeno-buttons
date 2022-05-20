<template>
  <button class="animatedButton">{{ msg }}</button>
</template>

<script>
export default {
  name: "AnimatedButton",
  props: {
    msg: {
      type: String,
    },
  },
};
</script>

<style scoped>
.animatedButton {
  background-color: deeppink;
  border: none;
  padding: 1rem;
  color: antiquewhite;
  font-size: 1rem;
}
</style>
