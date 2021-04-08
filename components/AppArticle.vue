<template>
  <div class="AppArticle">
    <TheNavButton />

    <main>
      <header>
        <h1>{{ title }}</h1>
      </header>
      <article>
        <slot></slot>
      </article>
    </main>
    <aside>
      <TheNav />
    </aside>
    <TheFooter />
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: 'Title',
      required: true,
    },
  },
}
</script>
<style lang="scss">
.AppArticle {
  article {
    font-size: var(--step-0);

    & > * + *,
    figure:not(:first-child),
    figure + * {
      margin-top: var(--space-l);
    }

    a,
    em {
      font-size: var(--step--1);
    }

    h2:not(:first-child) {
      margin-top: var(--space-2xl);
    }

    h2:first-child {
      margin-top: calc(var(--space-2xl) - var(--space-l));
    }

    h2 + * {
      margin-top: var(--space-s);
    }

    h2,
    h3,
    p {
      font-size: var(--step-0);
      margin-left: var(--space-m-l);
      max-width: var(--space-7xl);
    }

    p {
      hyphens: auto;
    }
  }

  article,
  header {
    display: flex;
    flex-flow: column nowrap;
    justify-content: space-around;
    min-height: 85vh;
    padding: var(--space-s-m);
  }

  h1 {
    text-align: center;
    font-size: var(--step-3);
  }

  h1,
  h2 {
    text-transform: uppercase;
  }

  h3 {
    font-family: var(--fontBody);
    font-weight: normal;
  }
}
</style>
