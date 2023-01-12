<template>
  <NavBar/>
  <router-view/>
  <FooterItem/>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import FooterItem from "./components/Footer.vue";
export default {
  components: {
    NavBar,
    FooterItem
  }
}
</script>

<style>
#app {
  font-family: 'Courier New', Courier, monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #B288C0;
}
</style>
