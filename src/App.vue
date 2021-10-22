<template>
  <div class="myApp">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {};
  },
};
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.myApp {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  /* background-color: azure; */
}
</style>
