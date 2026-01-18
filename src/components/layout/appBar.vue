<template>
  <v-app-bar position="fixed" color="white" elevation="1">
    <v-toolbar-title class="font-weight-bold">
      <v-img src="@/assets/logo-img.png" alt="Logo" contain height="32"></v-img>
    </v-toolbar-title>

    <v-spacer />

    <v-text-field
      prepend-inner-icon="mdi-magnify"
      label="Buscar produtos"
      density="compact"
      hide-details
      class="search-bar"
    />

    <v-spacer />

    <v-btn variant="text">Login</v-btn>
    <v-btn variant="text">Favoritos</v-btn>
    <v-btn variant="text">Carrinho</v-btn>
  </v-app-bar>
</template>

<script setup>
import { ref } from "vue";

const search = ref("");
</script>

<style scoped>
.search-bar {
  max-width: 900px;
}
</style>
