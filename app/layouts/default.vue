<template>
  <div class="container mx-auto max-w-3xl">
    <header class="flex justify-between items-center mt-5">
      <div>
        <NuxtLink to="/" class="text-xl font-semibold p-2 hover:bg-gray-200"
          >Victor</NuxtLink
        >
      </div>
      <Menu />
    </header>
    <main class="p-2">
      <slot />
    </main>
  </div>
</template>