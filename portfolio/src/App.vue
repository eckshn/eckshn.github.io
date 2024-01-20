<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ProfileCard/>
</template>

<script>
import Home from './components/Home.vue'
import ProfileCard from './components/ProfileCard.vue';

export default {
  name: 'App',
  components: {
    Home,
    ProfileCard
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
</style>
