<template>
  <div class="Hello">  <!-- Il faut dire Bonjour en anglais, comme ça, cela fait plus pro -->
    <h1>{{ msg }}</h1>
    <!-- Monsieur, il me faudrait la moyenne si voulez m'aider à sauver mon annee.. -->
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
