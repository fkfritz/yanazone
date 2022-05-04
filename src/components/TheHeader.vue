<script setup lang="ts"></script>

<template>
  <header class="px-20 flex-row align-items-center">
    <a href="#" class="mr-20">
      <span class="logo">Yanazone</span>
    </a>
    <ul class="flex-row flex-fill">
      <li class="mr-10">
        <a href="#">Boutique</a>
      </li>
      <li>
        <a href="#">Admin</a>
      </li>
    </ul>
    <ul class="flex-row">
      <li class="mr-10">
        <a href="#">Connexion</a>
      </li>
      <li>
        <a href="#">Inscription</a>
      </li>
    </ul>
  </header>
</template>

<style lang="scss" scoped>
header{
  display: flex;
  background-color: var(--primary-1);
  & a{
    color: var(--text-primary-color);
    & .logo{
      font-weight: 700;
      font-size: 20px;
    }
  }
  & ul{display: flex;}
}
</style>
