<template>
  <div id="app">
    <header>
      <h1>Bluepost's page</h1>
    </header>
    <div class="globalMenu">
      <router-link to="/">Home</router-link> | 
      <router-link to="/about">About</router-link> |
      <router-link to="/skills">Skills</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
body{
  background:#008cff;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
    background: #ffffff;
    width: 100%;
    text-align: center;
    box-shadow:0px 0px 10px 0px rgba(0, 0, 0, 0.25);
    margin: 10px, 10px, 10px, 10px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

div.globalMenu{
    background: #ffffff;
    width: 100%;
    text-align: center;
    /* box-shadow:0px 0px 10px 0px rgba(0, 0, 0, 0.25); */
    margin: 10px 0px 10px 0px;
    padding:10px 0px 10px 0px;
}


ul.nav {
    overflow:hidden;
    list-style:none;
}
     
ul li.navitem {
    display: inline-block;
    padding: 26px 20px 20px 20px;
    /* border-left: 1px solid #111111;
    border-right: 1px solid #111111; */
}


</style>
