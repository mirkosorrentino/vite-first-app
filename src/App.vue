<script>
import AppBanner from "./components/AppBanner.vue";

export default {
  components: {
    AppBanner
  },
  data(){
    return {
      title: "My title"
    }
  }
}
</script>

<template>
  <h1>Hello vue with vite {{ title }}</h1>
  <AppBanner />
  <AppBanner />
  <AppBanner />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
