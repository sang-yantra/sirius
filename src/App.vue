<template>
  <div id="app" class="font-bold">
    <puttu-banner />
    <my-story />
  </div>
</template>

<script>
import PuttuBanner from "./components/Banner/PuttuBanner.vue";
import MyStory from "./components/MyStory.vue";

export default {
  name: "App",
  components: {
    PuttuBanner,
    MyStory,
  },
};
</script>

<style>
body {
  background: url("@/assets/img/heart-particles.gif");
  background-size: cover;
  background-position: center;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
