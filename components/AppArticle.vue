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

    & > * + * {
      margin-top: var(--space-l);
    }

    h2,
    h3,
    p {
      font-size: var(--step-0);
      margin-left: var(--space-m-l);
      max-width: var(--space-7xl);
    }

    section:nth-of-type(3n-1) p:first-child,
    h3:first-child {
      // background-color: lime;
      text-indent: 25%;
    }

    section:nth-of-type(3n) p:first-child,
    h3:first-child {
      // background-color: yellow;
      text-indent: 50%;
    }

    section:nth-of-type(3n-2) p:first-child,
    h3:first-child {
      // background-color: blue;
      text-indent: 75%;
    }

    section:first-of-type p:first-child,
    h3:first-child {
      // background: mediumslateblue;
      text-indent: unset;
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

  em {
    font-size: var(--step--1);
  }
}
</style>
