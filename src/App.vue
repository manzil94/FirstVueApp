<template>
  <div id="app">
    <div id="nav">
      <div id="nav">
      <router-link to="/">Athlete</router-link> |
      <router-link to="/triathlete">Triathlete</router-link> |
      <router-link to="/Triathleteclimbing">Triathleteclimbing</router-link>
    </div>
    <router-view/>
    </div>
  </div>
</template>

<style lang="scss">

body{
  background-image: url('~@/assets/background.jpg');
}
  

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
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
