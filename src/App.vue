<template>
  <div id="app" class="h-screen w-screen bg-blue-100">
    <Home />
  </div>
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home
  }
};
</script>

<style src="./assets/tailwind.css"></style>
