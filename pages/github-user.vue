<script setup>
const { data: user } = useFetch("https://api.github.com/users/markotuya0");
</script>
<template>
  <h1>{{ user?.name }}</h1>
  <p>{{ user?.blog }}</p>
  <p>{{ user?.bio }}</p>
  <p>Public Repos = {{ user?.public_repos }}</p>
</template>
