<script setup>
const route = useRoute();
</script>
<template>
  <h1>user page {{ route.params.id }}</h1>
  <p>{{ route.query.search }}</p>
</template>
