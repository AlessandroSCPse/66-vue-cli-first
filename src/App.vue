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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  width: 100%;
  display: block;
}
</style>
