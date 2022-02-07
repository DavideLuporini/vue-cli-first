<template>
  <div id="app">
    <section id="Jumbo">
          
      </section>
  </div>
</template>

<script>
export default {
  name: 'Jumbo',
 
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#Jumbo {
  border: black 5px solid;
  background-image: url('https://content.fantacalcio.it/web/img/medium/giroud-5fe53b4b-090d-4488-95b3-9065e861927b.jpg');
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
  height: 500px;
}

img{
    max-width: 100%;
    height: 100%;
}
</style>