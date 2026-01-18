
<template>
  <v-app>
    <!-- Header fixo -->
    <AppBar />

    <!-- Conteúdo dinâmico (SPA) -->
    <v-main>
      <router-view />
    </v-main>

    <!-- Footer fixo -->
    <Footer />
  </v-app>
</template>

<script setup>
</script>

<style scoped>
/* Opcional: ajustes globais do layout */
</style>
