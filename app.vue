<template>
  <v-app id="inspire" :theme="useCartStore().getTheme">
    <RouterView />
  </v-app>
</template>

<script setup>
import { useCartStore } from "./stores/cart";
</script>
