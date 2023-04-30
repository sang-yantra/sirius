<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <header
    class="banner bottom-3 m-2 shadow-pink-300 rounded-xl shadow-2xl border-red-900 text-white object-contain"
  >
    <div class="banner__contents ml-7 pt-36 h-48">
      <h1 class="banner__title text-3xl font-extrabold pb-1">Puttu Pai</h1>
      <h2 class="banner__description pt-4 text-sm max-w-sm">
        Puttu Pai or Bharthi Pai, the first girl which entered my heart
      </h2>
    </div>
    <div class="banner__fadebottom h-12 rounded-xl"></div>
  </header>
</template>

<script>
export default {
  name: "puttu-banner",
};
</script>

<style>
.banner {
  background-image: url("@/assets/img/puttu-bg.jpg");
  background-size: cover;
  background-position: center center;
}

.banner__fadebottom {
  background-image: linear-gradient(
    180deg,
    transparent,
    rgba(37, 37, 37, 0.61),
    #111
  );
}
</style>
