<template>
  <div id="app">
    <Header />
    <Header />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import QuestionBox from './component/QuestionBx'

export default {
  name: 'app',
  components: {
    Header,
    QuestionBox
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
