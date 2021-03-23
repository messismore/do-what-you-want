<template>
  <div class="AppProject">
    <TheNavButton />
    <header>
      <h1>{{ name }}</h1>
      <h2>{{ author }}</h2>
      <slot name="header">Header Content</slot>
    </header>
    <main>
      <slot name="main">Main Content</slot>
    </main>
    <TheNav />
  </div>
</template>

<script>
export default {
  props: {
    author: { type: String, required: true },
    name: { type: String, required: true },
  },
}
</script>

<style lang="scss">
.AppProject {
  header,
  main {
    display: flex;
    min-height: 90vh;
    padding: var(--space-s-m);
  }

  h1,
  h2 {
    text-align: center;
    font-size: var(--step-1);
  }

  h2 {
    font-style: italic;
  }

  header {
    flex-flow: column nowrap;
    justify-content: space-around;
    margin-left: var(--space-m-l);
    position: relative;
    z-index: -1;

    & > * + * {
      margin-top: var(--space-s);
    }

    p:nth-of-type(2) {
      text-indent: var(--space-l);
    }
  }

  main {
    background: var(--colour-background);
    flex-flow: row wrap;
    padding-right: calc(-1 * var(--space-s));
    position: relative;
    z-index: 1;

    & > * {
      flex-grow: 1;
      margin-right: var(--space-s);
      margin-bottom: var(--space-2xs);
    }
  }
}
</style>
