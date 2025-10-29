<script setup>
import Counter from './components/Counter.vue'
</script>

<template>
  <div id="app">
    <Counter />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>