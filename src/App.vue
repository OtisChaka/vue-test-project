<template>
  <div class="container">
    This is a real thing
    <div class="w-10 h-10 bg-red-600"></div>
    <test></test>
  </div>
</template>

<script>
import test from "./components/test.vue";

export default {
  components: {
    test,
  },
};
</script>

<style>
html,
body,
template {
  margin: 0;
  color: white;
}
.container {
  width: 100%;
  min-height: 100vh;
  background-color: #121212;
}
</style>
