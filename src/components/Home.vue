<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      <b>And this is my portfolio. Check out my projects down below!</b>
    </p>
    <h3>In progress</h3>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
