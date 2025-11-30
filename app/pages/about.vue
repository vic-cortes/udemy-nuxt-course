<template>
  <div>
    <h1>Welcome to the Nuxt.js Course!</h1>
    <p>This is the about page.</p>
    <button @click="enableCustomLayout">Enable Custom Layout</button>
  </div>
</template>

<script setup>
function enableCustomLayout() {
  setPageLayout('another');
}

useHead({
  title: 'About',
});
</script>