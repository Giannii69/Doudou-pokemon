<template>
<div>
  <AjouterAuPanier msg=""/>
<HelloWorld msg=""/>
<Image msg=""/>
<Modification msg=""/>
<Shop msg=""/>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
  </div>
</div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AjouterAuPanier from './components/AjouterAuPanier.vue'
import Image from './components/Image.vue'
import Modification from './components/Modification.vue'
import Shop from './components/Shop.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    AjouterAuPanier,
    Image,
    Modification,
    Shop,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
