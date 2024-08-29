<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo layout-logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue layout-logo" alt="Vue logo" />
    </a>
  </div>
    <HelloWorld msg="Vite + Vue" />
</template>

<style lang="scss">
  @use './assets/scss/main.scss' 
</style>
