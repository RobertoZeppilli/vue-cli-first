<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Title />
    <Hero />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    // HelloWorld
    Title,
    Hero
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>


// Descrizione:
// Create un nuovo progetto utilizzando Vue CLI: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
// Create e utilizzate un componente Title, il quale contiene un titolo che recita "La mia prima app con Vue CLI!"
// Bonus:
// Creare un secondo componente Hero, che visualizza un jumbotron.