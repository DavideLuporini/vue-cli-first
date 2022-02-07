<template>
    <div id="app">
      <Title />
      <Jumbo />
    </div>
</template>

<script>
import Title from './components/Title.vue';
import Jumbo from './components/Hero.vue';
export default {
  name: 'App',
  components: {
    Title,
    Jumbo,
  }
}
</script>

<style>
body{
  background-color: rgb(75, 5, 5);
}
</style>