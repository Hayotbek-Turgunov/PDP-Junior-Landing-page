<template>
  <footer class="bg-[#012A30] h-[180px] pt-[39px]">
    <div class="max-w-[990px] mx-auto">
      <div class="flex items-center justify-between mb-[22px]">
        <a href="">
          <img class="w-[138px] h-[38px]" :src="headerLogo" alt="" />
        </a>

        <div class="flex gap-2">
          <div
            class="w-[32px] h-[32px] rounded-full bg-[#00B533] flex items-center justify-center"
          >
            <img :src="footerTelegram" alt="" />
          </div>

          <div
            class="w-[32px] h-[32px] rounded-full bg-[#00B533] flex items-center justify-center"
          >
            <img :src="footerInsta" alt="" />
          </div>

          <div
            class="w-[32px] h-[32px] rounded-full bg-[#00B533] flex items-center justify-center"
          >
            <img :src="footerYoutobe" alt="" />
          </div>
        </div>

        <a class="text-[#DBF9D8] text-[20px]" href="">(78) 777-47-47</a>
      </div>

      <hr class="text-[#DBF9D8] mb-[17px] font-medium" />
      <div class="flex justify-between">
        <span class="text-[12px] text-[#DBF9D8]">©2022 PDP Academy</span>
        <span class="text-[#DBF9D8] text-[12px]"
          >Xizmatlar litsenziyalangan</span
        >
      </div>
    </div>
  </footer>
</template>

<script setup>
import headerLogo from "../assets/icon/header-logo.svg";
import footerTelegram from "../assets/icon/telegr.svg";
import footerInsta from "../assets/icon/insta.svg";
import footerYoutobe from "../assets/icon/Youtube.svg";
</script>
