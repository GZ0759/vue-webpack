<template>
  <div id="app">
    <Page />
  </div>
</template>

<script>
import Page from "./pages/formPackage.vue";

export default {
  name: "app",
  components: {
    Page
  }
};
</script>

<style lang="scss">
@import "./assets/_reset.scss";
</style>

