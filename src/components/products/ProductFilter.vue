<template>
  <v-container class="align-center">
    <v-card class="pa-5" max-width="100%">
      <v-row no-gutters>
        <v-col cols="4" class="px-2">
          <v-select
            density="compact"
            hide-details
            label="Marca"
            :items="['Nike', 'Abibas', 'Puma']"
          />
        </v-col>

        <v-col cols="4" class="px-2">
          <v-select
            density="compact"
            hide-details
            label="Marca"
            :items="['Nike', 'Abibas', 'Puma']"
          />
        </v-col>

        <v-col cols="4" class="px-2">
          <v-select
            density="compact"
            hide-details
            label="Preço"
            :items="['menor', 'maior']"
          />
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>
