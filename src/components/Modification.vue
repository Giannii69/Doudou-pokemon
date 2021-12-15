<template>
  <div class="hello">
    <div class="etape-1">
    <h1>{{ msg }}</h1>
    <label for="salameche">Nombre de doudou (0-200):</label> <!-- Ici, vous pouvez choisir la quantité que vous voulez, de 1 à 200 -->

<input type="number" id="doudou" name="salameche"
       min="0" max="200">
  </div>
  <div class="etape-2">
    <h2>Choisir quel starter vous allez prendre</h2> <!-- Ici, il faut choisir quel starter de n'impore quel génération vous voulez choir, tout en noir ou tout en blanc -->
    </div>
    <div class="etape-3">
      <h2>Choisir son pokemon</h2>
      <div class="option">
        <label for="black color">
          <div class="white color">
          <input type="radio" id="white" name="white color" value="white" checked>
        </div>
        <span>Blanc</span>
        </label>
        <label for="black color">
          <div class="Black">
          <input type="radio" id="black" name="black color" value="black" checked>
          <img src="../assets/Noir.png" alt="noir">
        </div>
        <span>Noir</span>
        </label>
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
