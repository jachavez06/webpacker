<!-- This is a single file component. -->

<!-- Template for component -->
<template>
  <div id="app">
    <p>{{ message }}</p>
  </div>
</template>

<!-- JS for component -->
<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<!-- Styles for component -->
<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
