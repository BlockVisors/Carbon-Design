<template>
  <div id="app">
    <TutorialHeader />
   <router-view />
  </div>
</template>

<script>
import TutorialHeader from "./components/TutorialHeader";

export default {
  name: "App",
  components: {
    TutorialHeader,
  }
};
</script>

<style lang="scss">
@import "./styles/carbon";
</style>
