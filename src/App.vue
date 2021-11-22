<template>
  <div id="app">
    <Title/>
    <Jumbotron/>
  </div>
</template>

<script>
import Title from '@/components/Title.vue';
import Jumbotron from '@/components/Jumbotron.vue';

export default {
  name: 'App',
  components: {
    Title,
    Jumbotron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  background-image: url(./assets/arcane-topping-netflix-top-10s-2021.jpg);
  background-size: cover;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
