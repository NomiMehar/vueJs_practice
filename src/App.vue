<script setup>
import HelloWorld from './components/Home/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="container">
      <div class="header-wrapper">
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="50" height="50" />
      <HelloWorld />
    </div>
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style lang="scss">
@import './assets/main.scss';
</style>