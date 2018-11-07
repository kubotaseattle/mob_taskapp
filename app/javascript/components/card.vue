<template>
  <div>
    <ul>
      <input type="text" v-model="message">
      <input type="submit">
      <p>メッセージ：{{ message }}</p>
      <li v-for="card in cards">
        {{ card }}
      </li>
    </ul>
  </div>
</template>

<script>
  export default{
    data: function() {
      return {
        message: '',
        cards: [1,2,3]
      }
    }
  }
</script>

<style scope>
  li {
    width: 100px;
    margin-bottom: 5px;
    border: solid 1px;
  }
</style>
