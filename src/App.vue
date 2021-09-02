<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>
<style lang="scss">
html {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  padding: 0;
  margin: 0;  

}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 0;
  margin: 0;
  overflow-x: hidden; 
  background-color:  #FFF5F0;

}
</style>
