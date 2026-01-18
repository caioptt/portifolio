<template>
  <v-container class="pa-0">
    <v-card class="align-center, pa-3" max-width="344">
      <v-img
        src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
        height="250px"
        width="100%"
      ></v-img>
      <v-card-title>{{ product.name }}</v-card-title>
      <v-card-subtitle>{{ product.price }}</v-card-subtitle>
      <v-card-text> </v-card-text>
      <v-card-actions>
        <v-row>
          <v-col class="" cols="8"
            ><v-btn color="info" size="large" variant="flat"
              >Ver detalhes</v-btn
            ></v-col
          >
          <v-col class="pl-0" cols="4"
            ><v-btn
              color="black"
              size="large"
              variant="flat"
              prepend-icon="mdi-cart"
              append-icon="mdi-plus"
            ></v-btn
          ></v-col>
        </v-row>
      </v-card-actions>
    </v-card>
  </v-container>
</template>

<script setup lang="ts">
interface Product {
  id: number;
  name: string;
  price: number;
}

defineProps<{
  product: Product;
}>();
</script>
