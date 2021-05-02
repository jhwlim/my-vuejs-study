<template>
  <div id="app" class="app">
    <app-nav></app-nav>
    <router-view></router-view>
  </div>
</template>

<script>
import AppNav from './components/AppNav.vue'

export default {
  name: "app",
  components: {
    "app-nav": AppNav
  }
}
</script>

<style src="./assets/css/reset.css"></style>
<style>
</style>