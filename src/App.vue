<template>
  <div id="app">
    <MainTitle />
    <PageBanner />

    <h2>H2 dentro App.vue</h2>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import MainTitle from "./components/MainTitle.vue";
import PageBanner from "./components/PageBanner.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    MainTitle,
    PageBanner
  },
};
</script>

<style lang="scss">
@import './style/variables';
@import './style/common';
</style>
