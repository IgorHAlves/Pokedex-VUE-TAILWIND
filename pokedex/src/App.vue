<script setup>
import { ref } from "vue";

import Navbar from "./components/NavbarComponent.vue";

import Footer from "./components/FooterComponent.vue";
let num = ref(0);
</script>

<template>
  <div class="flex flex-col min-h-screen bg-black">
    <Navbar />

    <div class="main container mx-auto px-4 py-6">
      <router-view> </router-view>
    </div>

    <Footer />
  </div>
</template>
