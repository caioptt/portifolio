<template>
  <v-container>
    <Carousel />
    <ProductFilter />
    <v-container>
      <v-row class="align-center">
        <v-col
          v-for="product in products"
          :key="product.id"
          cols="12"
          sm="6"
          md="4"
          lg="2"
        >
          <ProductCard :product="product" />
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>
<script setup lang="ts">
import { ref } from "vue";

interface Product {
  id: number;
  name: string;
  price: number;
}

const products = ref<Product[]>([
  {
    id: 1,
    name: "Tenis nike air force 1",
    price: 99.99,
  },
  {
    id: 2,
    name: "Tenis adidas superstar",
    price: 129.99,
  },
  {
    id: 3,
    name: "Tenis puma rs-x",
    price: 149.99,
  },
  {
    id: 4,
    name: "Tenis reebok classic",
    price: 89.99,
  },
  {
    id: 5,
    name: "Tenis reebok classic",
    price: 89.99,
  },
  {
    id: 6,
    name: "Tenis reebok classic",
    price: 89.99,
  },
  {
    id: 7,
    name: "Tenis reebok classic",
    price: 89.99,
  },
  {
    id: 8,
    name: "Tenis reebok classic",
    price: 89.99,
  },
]);
</script>
