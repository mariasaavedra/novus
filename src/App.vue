<template>
  <div id="app">

  <nav class="navbar navbar-expand-lg p-4 navbar-dark bg-dark">
    <a class="navbar-brand" href="#"><img width="150px" class="pl-4 d-inline-block align-top" src="./assets/logo.png"></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  </nav>

  <router-view/>

  <div class="footer w-100 bg-dark p-4">
    <img width="150px" class="d-block align-top p-4" src="./assets/logo.png">
    <nav class="nav flex-row text-left">
      <a class="nav-link text-white" href="#">Services</a>
      <a class="nav-link text-white" href="#">Contact</a>
      <a class="nav-link text-white" href="#">Support</a>
    </nav>
  </div>

  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
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
