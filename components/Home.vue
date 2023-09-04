<template>
  <div class="flex md:flex-wrap">
    <div class="flex-1">
      <div class="flex justify-center mt-40">
        <h1 class="text-6xl lg:text-7xl font-black">
          Next <span class="text-accent">Med</span> Solution
        </h1>
      </div>
      <p class="p-2">
        เพิ่มประสิทธิภาพการบริการของโรงพยาบาลด้วยเว็บทันสมัยและสวยงาม
        ด้วยความเชี่ยวชาญในเว็บไซต์สำหรับโรงพยาบาลแต่ละแห่ง
      </p>
      <div class="mt-5 flex justify-center xl:justify-start">
        <button class="btn btn-primary w-40" @click="goToId('about')">
          About Me !
        </button>
      </div>
    </div>
    <div class="flex-2 hidden lg:block">
      <div class="flex justify-center mt-20">
        <img class="w-3/5" src="../assets/images/Work.svg" alt="" />
      </div>
    </div>
  </div>
</template>
<script setup>
useHead({
  title: "Next Med Solution",
});

function goToId(id) {
  window.location.href = "#" + id;
}
</script>
