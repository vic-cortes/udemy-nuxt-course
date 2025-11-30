<template>
  <div>Projects</div>

  <section v-if="pending">Loading...</section>
  <section v-else-if="error">Error: {{ error.message }}</section>
  <section v-else>display all data</section>
</template>

<script setup>
const { error, pending, data } = await useFetch(
  'https://api.github.com/users/vic-cortes/repos'
);
</script>