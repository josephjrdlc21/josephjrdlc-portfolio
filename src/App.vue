<template>
  <Home/>
</template>

<script>
import Home from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    Home
  },
}
</script>

<style>
  body{
    background: #f2f2f2;
    margin: 0;
  }
  #app{
    width: 100%;
    overflow: hidden;
    margin: 0;
    position: relative;
  }
</style>
