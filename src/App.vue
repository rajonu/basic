<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <HelloWorld msg="An Intelegent It Firm"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #17a2ff;
  margin-top: 60px;
}
</style>
