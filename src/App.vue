<template>
  <div id="app">
    <header>
        <h3>Tommi Aalto</h3>
        <nav>
            <a href="/html/">HTML</a> |
            <a href="/css/">CSS</a> |
            <a href="/js/">JavaScript</a> |
            <a href="/python/">Python</a>
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
  border: 1px solid red;
  display: flex;
  align-items: baseline;
}
nav {
  flex: 70%;
}
h3 {
  flex: 30%;
}
</style>
