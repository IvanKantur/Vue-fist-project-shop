<template>
  <div id="app">
    <Shop_component shop-title="Смартфоны"/>
    <Shop_component shop-title="Ноутбуки"/>
  </div>
</template>

<script>
  import Shop_component from "./components/Shop_component"

  export default {
    components: {
      Shop_component
    }
  }
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
      color: #42b983;
    }
  }
}
</style>
