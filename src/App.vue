<template>
  <nav>
    <div>
      <header>
        <router-link to="/"><img alt="Vue logo" src="./assets/logo.png" ></router-link>
        <router-link to="/about">About</router-link>|
        <router-link to="/works">Works</router-link>
      </header>
    </div>
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
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

header{ 
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  color: #2c3e50;
  
}
img{
  position:fixed;
  top:0px;
  left:30px;
  height: 100px;
}


</style>
