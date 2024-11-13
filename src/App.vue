<template>
  <header>
    <Header />
  </header>

  <main>
    <Hero />
    <Course />
    <CourseInfo />
    <Contact />
    <Addres />
  </main>

  <footer>
    <Footer />
  </footer>
</template>

<script setup>
import Header from "./components/Header.vue";
import Hero from "./components/Hero.vue";
import Course from "./components/CourseTarget.vue";
import CourseInfo from "./components/CourseInfo.vue";
import Contact from "./components/Contact.vue";
import Addres from "./components/Address.vue";
import Footer from "./components/Footer.vue";
</script>

<style lang="scss"></style>
