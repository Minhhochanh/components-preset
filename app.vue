<template>
  <div id="app">
    <headercomp />
    <bodycomp />
  </div>
</template>

<script>
import headercomp from './src/components/header-comp.vue';
import bodycomp from './src/components/body.vue';

export default {
  name: 'App',
  components: {
    headercomp,
    bodycomp,
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
}
</style>
