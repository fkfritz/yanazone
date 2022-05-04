<script setup lang="ts"></script>

<template>
  <div class="product">
    <div class="product-image"></div>
    <div class="p-10 d-flex flex-column">
      <h4>Montre connecté</h4>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius inventore
        vero labore fuga optio eligendi tempore repellendus cupiditate! 
      </p>
      <div class="d-flex flex-row align-items-center">
        <strong class="flex-fill">Prix : 200€</strong>
        <button class="btn btn-primary">Ajouter au panier</button>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.product{
  
  background-color: #fff;
  border: var(--border);
  border-radius: var(--border-radius);
  &-image{
    border-top-left-radius: var(--border-radius);
    border-top-right-radius: var(--border-radius);
    background-image: url(src/assets/montre.PNG);
    background-position: center;
    height: 200px;
    background-size: cover;
  }
}
</style>
