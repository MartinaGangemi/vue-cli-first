<template>
  <div id="app">
    <HelloWorld />
    <HeroComponent />
  
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import HeroComponent from './components/HeroComponent.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    HeroComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
*{
  margin:0;
  padding:0;
  border-sizing:border-box
}

</style>
