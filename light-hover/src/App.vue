<template>

  <CardContainer/>

  <a id="source-link" class="link" href="https://github.com/carlosperales95" target="_blank">
    <span class="roboto-mono">GitHub</span>
  </a>

</template>

<script>
import CardContainer from './components/CardContainer.vue';

export default {
  name: 'App',
  components: {
    CardContainer
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
