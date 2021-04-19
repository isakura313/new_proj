<template>
  <div id="app">
    <div class="columns is-multiline">
      <Card 
      img="https://cdn1.ozone.ru/s3/multimedia-d/6007526173.jpg"
      msg = "Таблетки для посудомоечной машины Finish AllinOne бесфосфатные, 100 шт" 
      price="1 205 ₽"
      />
      <Card 
      img="https://cdn1.ozone.ru/s3/multimedia-d/6007526173.jpg"
      msg = "Таблетки для посудомоечной машины Finish AllinOne бесфосфатные, 100 шт" 
      price="1 205 ₽"
      />
 
    </div>
  </div>
</template>

<script>
import Card from './components/Card.vue'

export default {
  name: 'App',
  components: {
    Card
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
