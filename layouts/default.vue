<template>
  <div class="layout-default">
    <Nuxt />
    <NuxtLink class="center" to="Imprint">Imprint</NuxtLink>
  </div>
</template>

<style lang="scss">
.layout-default {
  max-width: 100%;

  .center {
    text-align: center;
    display: flex;
    justify-content: center;
  }
}
</style>
