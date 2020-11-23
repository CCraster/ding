<template>
  <HelloDing />
</template>

<script>
import HelloDing from './components/HelloDing.vue';

export default {
  name: 'App',
  components: {
    HelloDing,
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
  height: 100%;
  /* margin-top: 60px; */
}
</style>
