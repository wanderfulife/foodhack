<template>
  <div class="hello">
    <div class="row">
      <div class="column1">
        <h1>{{ msg }}</h1>
      </div>
      <div class="column2">
        <button type="button" onclick="alert('Hello world!')">Contact</button>
      </div>
    </div>
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

.column1 {
  float: left;
  width: 10%;
}

.column2 {
  float: right;
  width: 10%;
}
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
