<template>
  <div id="app">
    <header>
      <img alt="Vue logo" src="./assets/logo.svg" />
      <p>Huowen Hu</p>
      <h1>You did it!</h1>
      <p>You've successfully created a project with Vite + Vue 3.</p>
    </header>
    <main>
      <MyName />
      <div class="documentation">
        <h2>Documentation</h2>
        <p>
          Vue's
          <a href="https://v3.vuejs.org/guide/introduction.html" target="_blank"
            >official documentation</a
          >
          provides you with all the information you need to get started.
        </p>
      </div>
    </main>
  </div>
</template>

<script>
import MyName from './components/MyName.vue'

export default {
  name: 'App',
  components: {
    MyName
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

header {
  margin-bottom: 40px;
}

header img {
  width: 100px;
}

header p {
  font-size: 1.2em;
  margin-top: 0;
}

header h1 {
  color: #42b983;
  font-size: 2em;
  margin: 0;
}

header p:last-of-type {
  font-size: 1.2em;
  color: #666;
}

main {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.documentation {
  text-align: left;
  max-width: 600px;
  margin-top: 20px;
}

.documentation h2 {
  font-size: 1.5em;
  margin-bottom: 10px;
}

.documentation p {
  margin: 5px 0;
}

.documentation a {
  color: #42b983;
  text-decoration: none;
}
</style>
