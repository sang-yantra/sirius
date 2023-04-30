<template>
  <div id="app">
    <puttu-banner />
  </div>
</template>

<script>
import PuttuBanner from "./components/Banner/PuttuBanner.vue";

export default {
  name: "App",
  components: {
    PuttuBanner,
  },
};
</script>

<style>
body {
  background-color: var(--bg-color-pink-100);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
