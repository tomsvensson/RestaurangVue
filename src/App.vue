<template>
  <nav>
    <router-link to="/">Start</router-link> |
    <router-link to="/menu">Lunchmeny</router-link> |
    <router-link to="/contact">Kontakta oss</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Tahoma, Geneva, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

p{
  font-size: 20px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  font-size: 24px;
}

nav a.router-link-exact-active {
  color: #b99342;
}
</style>