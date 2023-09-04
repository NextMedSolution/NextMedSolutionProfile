<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
<script setup>
const colorMode = useColorMode();
colorMode.preference = "light";
</script>
<style>
body {
  font-family: "Mali";
}
</style>
