<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h4>안녕하세요~~~</h4>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
