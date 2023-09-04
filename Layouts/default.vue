<template>
  <div class="container mx-auto">
    <Navbar />

    <slot />
    <div class="fixed bottom-10 right-0 h-16 w-16">
      <button class="btn btn-circle btn-primary" @click="toTop()">Top</button>
    </div>
  </div>
</template>
<script setup>
function toTop() {
  window.scrollTo(0, 0);
}
</script>
