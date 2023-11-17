<template>
  <router-view/>
</template>

<style>
html, body{
  padding: 0;
  margin: 0;
}

ul{
  list-style-type: none;
  padding: 0;
}
   
a{
  text-decoration: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}


nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
