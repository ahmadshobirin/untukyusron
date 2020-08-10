<template>
  <div id="app" class="bg-gray">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
    -->
    <nav class="bg-white px-8 pt-2 shadow-md">
      <div class="-mb-px flex justify-center">
        <a class="no-underline text-grey-dark border-b-2 border-teal-dark uppercase tracking-wide font-bold text-xs py-3 mr-8"
          href="#">
           <router-link to="/">Home</router-link>
        </a>
        <a class="no-underline text-grey-dark border-b-2 border-transparent uppercase tracking-wide font-bold text-xs py-3 mr-8"
          href="#">
          <router-link to="/about">About</router-link>
        </a>
      </div>
    </nav>
    <router-view/>
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
