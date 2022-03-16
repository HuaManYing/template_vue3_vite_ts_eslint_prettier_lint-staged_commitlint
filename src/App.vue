<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue';
import { version as vueVersion, name, description, main, files } from 'vue/package.json';
console.log('vueVersion', vueVersion);
console.log(name, description, main, files);
</script>

<template>
  <!-- <div>11</div> -->
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>

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
