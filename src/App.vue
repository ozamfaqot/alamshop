<script setup lang="ts">
import NavbarTop from "@/components/layout/NavbarTop.vue";
import Footer from "@/components/layout/Footer.vue";
import { RouterView } from "vue-router";
</script>

<template>
  <div class="min-h-screen flex flex-col bg-slate-50">
    <NavbarTop />
    <RouterView />
    <Footer />
  </div>
</template>
