<script setup lang="ts">
import TheHeader from "@/components/TheHeader.vue";
import TheCart from "@/components/cart/TheCart.vue";
import TheShop from "@/components/shop/TheShop.vue";
import TheFooter from "@/components/TheFooter.vue";
</script>

<template>
  <div class="app-container">
    <TheHeader class="header b1" />
    <TheShop class="shop b2" />
    <TheCart class="cart b3" />
    <TheFooter class="footer b4" />
  </div>
</template>

<style>
@import "./assets/base.scss";
@import "./assets/debug.scss";

.app-container {
  min-height: 100vh;
  display: grid;
  grid-template-areas: "header header" "shop cart" "footer footer";
  grid-template-columns: 75% 25%;
  grid-template-rows: 70px auto 60px;
}

.header {
  grid-area: header;
}

.shop {
  grid-area: shop;
}

.cart {
  grid-area: cart;
}

.footer {
  grid-area: footer;
}
</style>
