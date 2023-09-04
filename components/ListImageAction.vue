<template>
  <div class="flex justify-center">
    <div class="grid grid-cols-2 lg:grid-cols-4 gap-8 p-2 my-40">
      <div class="card shadow-md">
        <img class="w-64 mx-2" src="../assets/images/SearchApp.svg" alt="" />
      </div>
      <div class="card shadow-md">
        <img class="w-64 mx-2" src="../assets/images/engineering.svg" alt="" />
      </div>
      <div class="card shadow-md">
        <img class="w-64 mx-2" src="../assets/images/programming.svg" alt="" />
      </div>
      <div class="card shadow-md">
        <img class="w-64 mx-2" src="../assets/images/analysis.svg" alt="" />
      </div>
    </div>
  </div>
</template>
<script setup>
let listImage = [
  "SearchApp.svg",
  "programming.svg",
  "engineering.svg",
  "analysis.svg",
];
</script>
