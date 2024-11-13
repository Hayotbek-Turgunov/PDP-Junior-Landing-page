<template>
  <div class="hero">
    <div class="max-w-[1280px] mx-auto pt-[70px] relative">
      <div class="relative">
        <div
          class="border w-[483px] h-[463px] px-[39px] py-[33px] rounded-2xl bg-white relative z-10"
        >
          <h2 class="font-bold text-3xl mb-4">
            PDP Junior – IT kelajakni shu yerdan boshlang!
          </h2>

          <div class="flex gap-5 mb-[23px]">
            <div
              class="bg-[#DBF9D8] w-10 h-10 flex items-center justify-center rounded-full flex-shrink-0"
            >
              <span class="text-[27px] font-bold">1</span>
            </div>
            <div>
              <h2 class="text-[#00B534] text-[21px] font-bold mb-2">
                Sifatli Ta’lim
              </h2>
              <p>
                5 yildan beri katta-yu kichik dasturchilarni yetishtirib
                chiqarmoqda
              </p>
            </div>
          </div>

          <div class="flex gap-5 mb-[23px]">
            <div
              class="bg-[#DBF9D8] w-10 h-10 flex items-center justify-center rounded-full flex-shrink-0"
            >
              <span class="text-[27px] font-bold">2</span>
            </div>
            <div>
              <h2 class="text-[#00B534] text-[21px] font-bold mb-2">
                Bilim va ko’nikma
              </h2>
              <p>
                Yoshlar dasturlash va tanqidiy fikrlash ko'nikmalariga ega
                bo'lishmoqda
              </p>
            </div>
          </div>

          <div class="flex gap-5">
            <div
              class="bg-[#DBF9D8] w-10 h-10 flex items-center justify-center rounded-full flex-shrink-0"
            >
              <span class="text-[27px] font-bold">3</span>
            </div>
            <div>
              <h2 class="text-[#00B534] text-[21px] font-bold mb-2">Natija</h2>
              <p>
                Algoritmlar orqali masalalar yechib, kichik oʻyinlar yasashmoqda
              </p>
            </div>
          </div>
        </div>

        <!-- Absolute joylashuvli element -->
        <div
          class="w-[483px] h-[463px] bg-[#DBF9D8] absolute top-0 left-0 z-0 rotate-6 rounded-[21px]"
        ></div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.hero {
  background-image: url("../assets/img/hero-bg.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 772px;
}
</style>
