<template>
  <div class="TheNavButton">
    <NuxtLink to="/">DWYW</NuxtLink>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.TheNavButton {
  color: black;
  font-family: var(--fontDisplay);
  font-weight: bold;
  margin: var(--space-2xs);
  position: fixed;
  transform: rotate(180deg);
  writing-mode: vertical-lr;
  z-index: 0;

  a {
    text-decoration: none;

    &:visited {
      color: black;
    }
  }
}
</style>
