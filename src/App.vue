<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <a href="https://render.com/" target="_blank">
      <img src="./assets/render.svg" class="logo render" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue + Render" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: 0.4s all ease;
}
.logo:hover {
  filter: drop-shadow(0 0 2em rgba(100, 108, 255, 0.667));
  transform: translateY(-20px);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em rgba(66, 184, 131, 0.667));
}
.logo.render:hover {
  filter: drop-shadow(0 0 2em rgba(125, 251, 97, 0.667));
}
</style>
