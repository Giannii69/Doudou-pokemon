<template>
  <div id="app">
    <img alt="salameche" src="salameche.jpg"> <!-- voici l'image de garde, une photo de salamèche qui represente le starter pokemon le plus connu -->
  </div>
</template>

<script>
export default {
  name: 'Image',
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