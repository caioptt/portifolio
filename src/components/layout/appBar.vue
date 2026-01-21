<template>
  <v-app-bar position="fixed" color="black" elevation="1">
    <v-toolbar-title class="pt-1">
      <v-img 
        width="210px"
        height="210px"
        src="@/assets/logo-img-w.png"
        alt="Logo"
        contain
      ></v-img>
    </v-toolbar-title>

    <v-spacer />

    <v-text-field
      v-model="search"
      prepend-inner-icon="mdi-magnify"
      variant="underlined"
      density="compact"
      hide-details
    />

    <v-spacer />

    <v-btn variant="text">Login</v-btn>
    <v-btn variant="text">Favoritos</v-btn>
    <v-btn variant="text">Sacola</v-btn>
  </v-app-bar>
</template>

<script setup>
import { ref } from "vue";

const search = ref("");
</script>

<style scoped></style>
