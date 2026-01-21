<template>
  <v-footer class="d-flex align-center justify-center ga-2 flex-wrap flex-grow-1 py-3" color="black">
    <v-btn
      variant="text"
      rounded
    ></v-btn>

    <div class="text-center mt-2" max-height="100px">
      {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
    </div>
  </v-footer>
</template>