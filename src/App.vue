<!-- src/App.vue -->
<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </nav>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
/* Add some basic styling */
nav {
  display: flex;
  gap: 1rem;
  margin-bottom: 1rem;
}

router-link {
  text-decoration: none;
}
</style>
