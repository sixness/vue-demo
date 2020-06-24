<template>
  <div id="app">
    <img alt="Vue logo" class="logo" src="./assets/logo.svg">
    <MainContent 
    title="Welcome to sixness Vue App"
    content="This is sixness Vue App."
    />
  </div>
</template>

<script>
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    MainContent
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
.logo {
  max-width :200px
}
</style>