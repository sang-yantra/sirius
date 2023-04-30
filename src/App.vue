<template>
  <div id="app" class="font-bold">
    <puttu-banner />
    <my-story />
    <audio controls autoplay>
      <source src="@/assets/audio/Puttu-samjhawan.mp3" type="audio/mpeg" />
      Your browser does not support the audio element.
    </audio>
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
  data() {
    return {};
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
