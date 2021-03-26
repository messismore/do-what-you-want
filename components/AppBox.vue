<template>
  <div class="AppBox" :style="styles">
    <nuxt-picture v-if="image" :src="image" v-bind="$attrs" />
    <video v-if="video" v-bind="$attrs">
      <source :src="video" />
      Sorry, your browser doesn't appear to support embedded videos.
    </video>
    <div>{{ index }}</div>
    <slot name="default"></slot>
  </div>
</template>

<script>
export default {
  inheritAttrs: false,
  props: {
    width: {
      validator: (value) => ['small', 'medium', 'large'].includes(value),
      default: 'medium',
    },
    align: {
      validator: (value) => ['top', 'bottom', 'center'].includes(value),
      default: 'top',
    },
    image: {
      type: String,
      required: false,
      default: null,
    },
    video: {
      type: String,
      required: false,
      default: null,
    },
  },
  computed: {
    styles() {
      return {
        '--align-self':
          this.align === 'top'
            ? 'flex-start'
            : this.align === 'bottom'
            ? 'flex-end'
            : 'center',
        '--width':
          this.width === 'small'
            ? 'var(--space-3xl)'
            : this.width === 'medium'
            ? 'var(--space-4xl-5xl)'
            : 'var(--space-6xl-7xl)',
      }
    },
    index() {
      return this.$parent.$children.length - 1
    },
  },
}
</script>

<style lang="scss">
.AppBox {
  --align-self: flex-start;
  --width: auto;
  align-self: var(--align-self);
  font-size: var(--step--1);
  max-width: min(calc(1.5 * var(--width)), 100vw);
  width: var(--width);

  a {
    font-size: var(--step--2);
  }

  img,
  picture,
  video {
    background-color: white;
    vertical-align: middle;
    width: 100%;
  }
}
</style>
