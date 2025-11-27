<template>
  <div>
    <h1>Blog Post {{ route.params.id }}</h1>
    <p>This is the blog post content.</p>
  </div>
</template>

<script setup>
const route = useRoute();
</script>