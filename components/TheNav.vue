<template>
  <nav class="TheNav">
    <ul>
      <li v-for="(value, key) in links" :key="key.title">
        <NuxtLink :to="key">
          <div class="title">{{ value.title }}</div>
          <div class="author">{{ value.author }}</div>
        </NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      links: {
        why: { title: 'Why and How to Do What You Want' },
        how: { title: 'Working in Miro and Webex' },
        cash: { title: 'Workshop Cashflow' },
        cycles: { title: 'Cycles', author: 'Felix Deiters' },
        project1: { title: 'Wird noch schöner', author: 'Keine Sorge' },
        project2: { title: 'project', author: 'author' },
        project3: { title: 'project', author: 'author' },
        project4: { title: 'project', author: 'author' },
        project5: { title: 'project', author: 'author' },
        project6: { title: 'project', author: 'author' },
        project7: { title: 'project', author: 'author' },
        project8: { title: 'project', author: 'author' },
        project9: { title: 'project', author: 'author' },
        project10: { title: 'project', author: 'author' },
        project11: { title: 'project', author: 'author' },
      },
    }
  },
}
</script>

<style lang="scss">
.TheNav ul {
  display: flex;
  flex-flow: column nowrap;
  justify-content: space-around;
  list-style: none;
  min-height: 100vh;
  padding: var(--space-l);
  text-align: center;
  text-transform: uppercase;

  a {
    text-decoration: none;
  }

  li + li {
    margin-top: var(--space-m);
  }

  .author {
    font-style: italic;
  }
}
</style>
