<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
    <MasterHelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    <AsyncViteComp />
  </div>
</template>

<script lang="ts" setup>
import MasterHelloWorld from './components/MasterHelloWorld.vue'
import AsyncViteComp from './components/AsyncViteComp.vue'

console.log('see MasterHelloWorld', MasterHelloWorld)

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
