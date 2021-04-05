<template>
  <figure class="AppImage">
    <nuxt-picture :src="image" v-bind="$attrs" />
    <figcaption>
      <slot></slot>
    </figcaption>
  </figure>
</template>

<script>
export default {
  inheritAttrs: false,
  props: {
    image: {
      type: String,
      required: false,
      default: null,
    },
  },
}
</script>

<style lang="scss">
.AppImage {
  font-size: var(--step--1);
  display: flex;
  gap: var(--space-3xs);

  // a,
  // em,
  // sup {
  //   hyphens: none;
  //   font-size: var(--step--2);
  // }

  figcaption {
    transform: rotate(180deg);
    writing-mode: vertical-lr;
  }

  img,
  picture {
    background-color: white;
    vertical-align: middle;
    width: 100%;
  }
}
</style>
