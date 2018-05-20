<template>
  <div id="app">
    <app-header></app-header>
  </div>
</template>

<script>
import Header from './components/header/Header'
export default{
  name: 'App',
  components: {
    'app-header': Header
  }
}
</script>

<style>
</style>
