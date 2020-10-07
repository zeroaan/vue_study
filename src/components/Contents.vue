<template>
  <div class="hello">
    <h2>Hello HelloWorld</h2>
    <p>{{ value }}</p>
  </div>
</template>

<script>
export default {
  name: "Contents",
  props: {
    value: String,
  },
};
</script>

<style scoped>
</style>
