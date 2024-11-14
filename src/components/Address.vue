<template>
  <div class="bg-[#00B534] h-[82px] font-bold flex items-center justify-center">
    <h2 class="text-center text-[33px] text-white">Bog'anish uchun</h2>
  </div>

  <div class="flex items-center">
    <img class="w-[50%] h-[507px] object-cover" :src="addressImg" alt="" />

    <img class="w-[50%] h-[507px] object-cover" :src="addressGps" alt="" />
  </div>
</template>

<script setup>
import addressImg from "../assets/img/addressImg.png";
import addressGps from "../assets/img/addressImg2.png";
</script>
