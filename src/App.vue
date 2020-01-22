<template>
  <div id="app">
    <!-- <router-view/> -->
    <h1>Vuex</h1>
    <app-result></app-result>
    <app-another-result></app-another-result>
    <hr>
    <app-counter></app-counter>
  </div>
</template>

<script>
import Counter from './components/Counter.vue'
import Result from './components/Result.vue'
import AnotherResutl from './components/AnotherResult.vue'

export default {
  name: 'App',
  data() {
    return {
      
    }
  },
  components: {
    appCounter: Counter,
    appResult: Result,
    appAnotherResult: AnotherResutl,
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
