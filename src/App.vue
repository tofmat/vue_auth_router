<template>
  <div id="app">
    <Navbar/>
    <div class="container">
    <router-view></router-view>
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
export default {
  name: 'app',
  components: {
    Navbar
  }
};
</script>

<style>
* {
  border-radius: 0px !important;
}
  body{
    background-color: aquamarine;
  }
</style>
