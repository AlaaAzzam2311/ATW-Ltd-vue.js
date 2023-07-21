<template>
  <div id="app">
    <Portfolio />
  </div>
</template>

<script>
import Portfolio from "./components/Portfolio.vue";

export default {
  components: {
    Portfolio,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #eebf63;
      font-family: Poppins;
      font-weight: 700;
      size: 16px;
      line-height: 24px;
      text-align: Center;
    }
  }
}
</style>
