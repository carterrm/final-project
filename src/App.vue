<template>
  <div id="app">
    
    <div id="header">
      <h1>Eagle Flight Academy</h1>
      <h2>Student Portal</h2>
    </div>

    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/Aircraft">Reservations</router-link> |
      <router-link to="/Logbook">Logbook</router-link>
    </div>
    <router-view/>
    <div class='footer'>
    <a href="https://github.com/carterrm/project-5">GitHub repository link</a>
  </div>
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
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #123356;
}

#nav a.router-link-exact-active {
  color: #123356;
}

h1 {
  font-size:3em;
  font-family:"Roboto";
}

h2 {
  font-size:2em;
  color: #808080;
}

.footer {
    text-align: center;
    color: #123356;
    margin-bottom:30px;
}

</style>
