<template>
  <div id="app">
    <TheTitle/>
    <TheJumbotron/>
  </div>
</template>

<script>
import TheTitle from "./components/TheTitle.vue";
import TheJumbotron from "./components/TheJumbotron.vue";
export default{
  name: 'App',
  components: {
    TheTitle,
    TheJumbotron,
    TheJumbotron
},
};
</script>

<style>
</style>
