<template>
  <div id="app">
    <status/>
  </div>
</template>

<script>
  import status from './components/status';

  export default {
    components: {
      status
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
