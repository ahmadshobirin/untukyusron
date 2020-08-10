<template>
  <div id="app" class="bg-gray">
    <nav class="bg-white px-8 pt-2 shadow-md">
      <div class="-mb-px flex justify-center">
        <router-link class="no-underline text-grey-dark border-b-2 uppercase tracking-wide font-bold text-xs py-3 mr-8"
          to="/">Home</router-link>
        <router-link class="no-underline text-grey-dark border-b-2 uppercase tracking-wide font-bold text-xs py-3 mr-8"
          to="/about">About</router-link>
      </div>
    </nav>
    <router-view />
  </div>
</template>

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
    color: #2c3e50;
  }

  #nav a.router-link-exact-active {
    color: #42b983;
  }
</style>