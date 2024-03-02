<script setup>
import { RouterView } from "vue-router";
import NavbarComponent from "./components/Navbar.vue";
import FooterComponent from "./components/Footer.vue";
</script>

<template>
  <NavbarComponent />

  <RouterView />

  <br><br>
  <br><br>
  <FooterComponent />
</template>

<style>
.bg-white {
  background-color: #121212; /* Karanlık arka plan rengi */
}

.text-gray-900 {
  color: #ffffff; /* Beyaz renkli metinler */
}

.text-gray-600 {
  color: #cccccc; /* Gri tonlu metinler */
}

.text-indigo-600 {
  color: #3b82f6; /* Mavi tonlu metinler */
}

.bg-indigo-600 {
  background-color: #3b82f6; /* Mavi tonlu arka planlar */
}

/* Diğer bileşenlerin renkleri ve stilleri buraya ekleyebilirsiniz */
body {
  background-color: #121212; /* Karanlık arka plan rengi */
  color: #ffffff; /* Beyaz renkli metinler */
}

a {
  color: #3b82f6; /* Mavi tonlu linkler */
}
</style>
