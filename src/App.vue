<template>
  <div id="app">
    <header>
        <h3>Tommi Aalto</h3>
        <nav>
            <a href="/html/">Blog</a> |
            <a href="/css/">Projects</a> |
            <a href="/js/">Contact</a>
        </nav>
    </header>
    <HomePage msg="Welcome to My Vue.js App"/>
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'app',
  components: {
  HomePage
  }
}
</script>

<style>
body {
  background-image: url("./assets/background_tracks.jpg");
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: linen;
  margin: 24px 48px 24px 48px;
  border: 1px solid black;
  border-radius: 35px;
}
header {
  display: flex;
  align-items: baseline;
  border-bottom: 2px solid black;
}
nav {
  flex: 70%;

}
h3 {
  flex: 30%;
}
</style>
