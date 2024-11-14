<template>
  <div class="bg-[#00B534] h-[82px] font-bold flex items-center justify-center">
    <h2 class="text-center text-[33px] text-white">PDP Junior kurslari</h2>
  </div>

  <div class="relative mt-24">
    <div class="max-w-[990px] mx-auto">
      <div
        class="border w-[990px] h-[350px] px-[39px] py-[33px] rounded-2xl bg-white relative z-10 flex gap-[89px] pb-[33px]"
      >
        <div>
          <img :src="courseRoboto" alt="" />
        </div>

        <div class="mt-10">
          <h3 class="text-[33px] font-bold leading-10 inline-block mb-4">
            Robototexnika
          </h3>
          <button class="bg-[#00B534] px-4 py-2 rounded-full text-white ml-3">
            Yangi
          </button>

          <ul class="mb-8">
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robot elektronikasini yig'ishni
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robototlarga erkin dastur yozish C++ tilida
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Motorlar va Sensorlarni ishlata olib
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Korpuslarni 3D Ko'rinishda yaratish
            </li>
          </ul>

          <div class="flex gap-14">
            <div>
              <h3 class="text-[23px] font-semibold">Davomiligi</h3>
              <span
                class="text-[22px] text-center block text-[#00B534] font-bold"
                >8 oy</span
              >
            </div>
            <div>
              <h3 class="text-[23px] font-semibold">Yosh chegarasi</h3>
              <span
                class="text-[22px] text-center block text-[#00B534] font-bold"
                >10 - 17</span
              >
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[990px] h-[312px] bg-[#DBF9D8] absolute top-0 left-50px z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>
  </div>

  <div class="relative mt-24">
    <div class="max-w-[990px] mx-auto">
      <div
        class="border w-[990px] h-[350px] px-[39px] py-[33px] rounded-2xl bg-white relative z-10 flex gap-[170px] items-center pl-[110px] pb-[33px]"
      >
        <div>
          <img :src="courseFront" alt="" />
        </div>

        <div class="mt-10">
          <h3 class="text-[33px] font-bold leading-10 inline-block mb-4">
            Robototexnika
          </h3>
          <button class="bg-[#00B534] px-4 py-2 rounded-full text-white ml-3">
            Yangi
          </button>

          <ul class="mb-8">
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robot elektronikasini yig'ishni
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robototlarga erkin dastur yozish C++ tilida
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Motorlar va Sensorlarni ishlata olib
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Korpuslarni 3D Ko'rinishda yaratish
            </li>
          </ul>

          <div class="flex gap-14">
            <div>
              <h3 class="text-[23px] font-semibold">Davomiligi</h3>
              <span
                class="text-[22px] text-center block text-[#00B534] font-bold"
                >8 oy</span
              >
            </div>
            <div>
              <h3 class="text-[23px] font-semibold">Yosh chegarasi</h3>
              <span
                class="text-[22px] block text-center text-[#00B534] font-bold"
                >10 - 17</span
              >
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[990px] h-[312px] bg-[#DBF9D8] absolute top-0 left-50px z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>
  </div>

  <div class="relative mt-24">
    <div class="max-w-[990px] mx-auto">
      <div
        class="border w-[990px] h-[350px] px-[39px] py-[33px] rounded-2xl bg-white relative z-10 flex gap-[89px] pb-[33px]"
      >
        <div>
          <img :src="coursePython" alt="" />
        </div>

        <div class="mt-10">
          <h3 class="text-[33px] font-bold leading-10 inline-block mb-4">
            Robototexnika
          </h3>
          <button class="bg-[#00B534] px-4 py-2 rounded-full text-white ml-3">
            Yangi
          </button>

          <ul class="mb-8">
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robot elektronikasini yig'ishni
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robototlarga erkin dastur yozish C++ tilida
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Motorlar va Sensorlarni ishlata olib
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Korpuslarni 3D Ko'rinishda yaratish
            </li>
          </ul>

          <div class="flex gap-14">
            <div>
              <h3 class="text-[23px] font-semibold">Davomiligi</h3>
              <span
                class="text-[22px] block text-center text-[#00B534] font-bold"
                >8 oy</span
              >
            </div>
            <div>
              <h3 class="text-[23px] font-semibold">Yosh chegarasi</h3>
              <span class="text-[22px] text-[#00B534] font-bold">10 - 17</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[990px] h-[312px] bg-[#DBF9D8] absolute top-0 left-50px z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>
  </div>

  <div class="relative mt-24">
    <div class="max-w-[990px] mx-auto">
      <div
        class="border w-[990px] h-[350px] px-[39px] py-[33px] rounded-2xl bg-white relative z-10 flex gap-[130px] items-center pl-20 mb-[92px] pb-[33px]"
      >
        <div>
          <img :src="courseScratch" alt="" />
        </div>

        <div class="mt-10">
          <h3 class="text-[33px] font-bold leading-10 inline-block mb-4">
            Robototexnika
          </h3>
          <button class="bg-[#00B534] px-4 py-2 rounded-full text-white ml-3">
            Yangi
          </button>

          <ul class="mb-8">
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robot elektronikasini yig'ishni
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Robototlarga erkin dastur yozish C++ tilida
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Motorlar va Sensorlarni ishlata olib
            </li>
            <li class="text-[18px] text-[#012A30] font-normal">
              - Korpuslarni 3D Ko'rinishda yaratish
            </li>
          </ul>

          <div class="flex gap-14">
            <div>
              <h3 class="text-[23px] font-semibold">Davomiligi</h3>
              <span
                class="text-[22px] block text-center text-[#00B534] font-bold"
                >8 oy</span
              >
            </div>
            <div>
              <h3 class="text-[23px] font-semibold">Yosh chegarasi</h3>
              <span class="text-[22px] text-[#00B534] font-bold">10 - 17</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Absolute joylashuvli element -->
      <div
        class="w-[990px] h-[312px] bg-[#DBF9D8] absolute top-0 left-50px z-0 rotate-2 rounded-[21px]"
      ></div>
    </div>
  </div>
</template>

<script setup>
import courseRoboto from "../assets/img/robototeh.png";
import courseFront from "../assets/img/front.png";
import coursePython from "../assets/img/python.png";
import courseScratch from "../assets/img/scratch.png";
</script>

<style></style>
