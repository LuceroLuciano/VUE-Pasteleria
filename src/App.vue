<template>
  <nav>
    <router-link to="/">Incio</router-link> 
    <router-link to="/about">Hacer Pedido</router-link> 
    <router-link to="/show">Ver Pedidos</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  background-color: #f386a6;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  padding-left: 15px;
}

nav a.router-link-exact-active {
  color: #fff /*#42b983*/;
}
</style>
