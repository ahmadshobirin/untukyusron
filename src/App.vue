<template>
  <div>
    <nav class="bg-white px-8 pt-2 shadow-md">
      <div class="-mb-px flex justify-center">
        <router-link class="no-underline text-grey-dark border-b-2 uppercase tracking-wide font-bold text-xs py-3 mr-8"
          to="/">Home</router-link>
        <router-link class="no-underline text-grey-dark border-b-2 uppercase tracking-wide font-bold text-xs py-3 mr-8"
          to="/about">About</router-link>
        <router-link class="no-underline text-grey-dark border-b-2 uppercase tracking-wide font-bold text-xs py-3 mr-8"
          to="/contact">Contact</router-link>
      </div>
    </nav>
    <router-view />
  </div>
</template>