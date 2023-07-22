<script setup>
import Navbar from "./views/Navbar.vue";
import Hero from "./views/Hero.vue";
import Services from "./views/Services.vue";
import { ref } from "vue";

const navbarElements = ref(["Home", "Buy", "Sell", "Contact Us"]);
</script>

<template>
  <header>
    <Navbar :navbar-elements="navbarElements" />
    <Hero :headline="32" />
    <div class="d-flex justify-content-evenly mx-5 px-5">
      <img src="/Images/company.png" alt="" />
      <img src="/Images/company.png" alt="" />
      <img src="/Images/company.png" alt="" />
      <img src="/Images/company.png" alt="" />
    </div>
    <Services />
  </header>
</template>
