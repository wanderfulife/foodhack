<template>
  <div class="hello">
    <button type="button"  class="rounded-md p-2 bg-purple-400 text-white" onclick="ethereum.request({ method: 'eth_requestAccounts' })">CONTACT</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

button {
  background-color: #ca06e7;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: columns;;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 12px;
}

</style>
