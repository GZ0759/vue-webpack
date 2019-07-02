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
@import "./style/_reset.scss";
#app {
  width: 100%;
  max-width: 640px;
  margin: 0 auto;
}
</style>

