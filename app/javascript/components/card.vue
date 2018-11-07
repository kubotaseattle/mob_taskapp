<template>
  <div>
    <p v-for="card in cards">
      {{ card }}
    </p>
  </div>
</template>

<script>
  export default{
    data: {
      cards: [1,2,3]
    }
  }
</script>

<style scope>
  div {
    border: solid 1px;
  }
</style>
