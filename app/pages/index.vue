<template>
  <div>
    <h1>Welcome to the Nuxt.js Course!</h1>
    <p>This is the home page.</p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: 'Main Page - Nuxt.js Course',
  description: 'This is the main page of the Nuxt.js course application.',
  ogTitle: 'Main Page - Nuxt.js Course',
  ogDescription: 'This is the main page of the Nuxt.js course application.',
  ogImage: '/main-page-image.png',
  ogUrl: 'https://www.nuxtjscourse.com/main',
  twitterTitle: 'Main Page - Nuxt.js Course',
  twitterDescription:
    'This is the main page of the Nuxt.js course application.',
  twitterImage: '/main-page-image.png',
  twitterCard: 'summary',
});

useHead({
  htmlAttrs: {
    lang: 'en',
  },
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: '/favicon.png',
    },
  ],
});
</script>