<template>
  <div id="app">
    <router-link to="/">Home | </router-link>
    <router-link to="/about">about</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
  created() {}
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin-left: 5px;
  margin-bottom: 5px;
}
a {
  text-decoration: none;
  font-size: 24px;
  font-weight: 600;
  color: #2c3e50;
}
a:active {
  color: aqua;
}
</style>
