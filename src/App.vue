<template>
  <header>this erea is header</header>
  <router-link to="/">Home</router-link> |
  <router-link to="/about">About</router-link>
  <div>
    <router-view />
    <Home />
  </div>
</template>

<script>
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
