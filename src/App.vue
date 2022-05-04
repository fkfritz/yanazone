<script setup lang="ts">
import TheHeader from '@/components/TheHeader.vue'
import TheCart from '@/components/cart/TheCart.vue'
import TheShop from '@/components/shop/TheShop.vue'
import TheFooter from '@/components/TheFooter.vue'
</script>

<template>
  <div class="app-container d-flex flex-column">
    <TheHeader class="header b1" />
    <div class="mt-70 d-flex flex-row">
      <TheShop class="shop" />
      <TheCart class="cart b3" />
    </div>
    <TheFooter class="footer b4" />
  </div>
</template>

<style lang="scss">
@import './assets/base.scss';
@import './assets/debug.scss';

header {
  position: fixed;
  width: 100%;
  height: 70px;
}

.shop {
  width: 75%;
}

.cart {
  width: 25%;
}

footer {
  height: 60px;
}
</style>
