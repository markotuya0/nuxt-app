<script setup>
useHead({
  title: "Home page",
  script: ["main.js"],
  meta: [{ name: "description", content: "this website is about nuxtjs" }],
});
</script>
<template>
  <h1>Home page</h1>
  <NuxtLink to="/about"> Go to About Page</NuxtLink>
</template>
