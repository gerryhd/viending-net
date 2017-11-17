<template>
  <div id="main-frame" class="column is-half is-offset-one-quarter">
    <div id="app">
            <h1>{{ welcomeMessage }}</h1>
            <router-view/>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      welcomeMessage: 'WHAT TO WATCH?'
    }
  }
}
</script>

<style>
@import '../node_modules/bulma/css/bulma.css';
@import './assets/styles.css';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
