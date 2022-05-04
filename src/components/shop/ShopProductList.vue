<script setup lang="ts">
import ShopProduct from '@/components/shop/ShopProduct.vue'
</script>

<template>
  <div class="grid p-20">
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
    <ShopProduct />
  </div>
</template>

<style scoped lang="scss">
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-auto-rows: 400px;
  gap: 20px;
}

</style>
