<template>
  <div class="dark:bg-slate-800">
    <Header />
    <div class="mx-auto max-w-screen-xl dark:bg-slate-800 dark:text-white p-4 min-h-screen">
      <slot />
    </div>
    <Footer />
  </div>
</template>

<script setup>

</script>

<style>
body {
  color: #1e293b;
}
</style>