<template>
  <C02DeclarativeRendering />
  <C01HelloWorld />
  <hr />
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import C01HelloWorld from './components/C01HelloWorld.vue';
import C02DeclarativeRendering from './components/C02DeclarativeRendering.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    C01HelloWorld,
    C02DeclarativeRendering,
  },
};
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
