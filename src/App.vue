<template lang="pug">
  div
    h1(class="title") {{ greeting }}

</template>

<script>
export default {
  props: ['greeting', 'who']
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
