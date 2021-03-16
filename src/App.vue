<template>
  <div id="app">
    <Background />
    <Content />
  </div>
</template>

<script>
import Background from "./components/Background.vue";
import Content from "./components/Content.vue";
export default {
  name: "App",
  components: {
    Background,
    Content,
  },
};
</script>

<style>
#app {
  margin: 0;
  padding: 0;
}
html,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Fira Code", monospace;
}
</style>
