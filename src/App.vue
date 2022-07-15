<template>
  <div id="app">
    <Feed />
  </div>
</template>

<script>
import Feed from "./components/feed.vue";
export default {
  name: "App",
  components: {
    Feed,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap");
body {
  background: #111;
}
#app {
  font-family: "Inter", Helvetica, Arial, sans-serif;
  max-width: 576px;
  margin: 0 auto;
  background: #444;
  padding: 2rem;
  text-align: center;
  display: flex;
  height: 100vh;
  align-content: center;
  justify-content: center;
  flex-direction: column;
}
</style>
