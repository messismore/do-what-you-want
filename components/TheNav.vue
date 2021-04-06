<template>
  <nav class="TheNav">
    <ul>
      <li v-for="(value, key) in links" :key="key.title">
        <NuxtLink :to="'/' + key">
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
        how: { title: 'Studio' },
        cashflow: { title: 'Cashflow Workshop' },
        pantheismus: {
          title: 'Pantheismus in der Stadt',
          author: 'Lotta Arndt',
        },
        terrapolis: {
          title: 'Terrapolis',
          author: 'Mascha Arnold und Jakob Köchert',
        },
        ringbahn: {
          title: 'Walking (the Ringbahn) as an Aesthetic Practice',
          author: 'Chloé Borreguero',
        },
        cycles: { title: 'Cycles', author: 'Felix Deiters' },
        blumenthal: { title: 'Blumenthal', author: 'Ricarda Brunner' },
        atmosphaeren: {
          title: 'Zur Zerlegung von Atmosphären',
          author: 'Yvan Leroy',
        },
        keller: {
          title: 'Gesellschaft der Nebenräume',
          author: 'Tobias Michnik',
        },
        recycling: {
          title: 'Von dem Häusern und dem Tagebau',
          author: 'Leander Nowack',
        },
        baustelle: {
          title: 'Baustellen' + '\u{200b}' + 'praxis', // eslint-disable-line
          author: 'Philine Rzadtki',
        },
      },
    }
  },
}
</script>

<style lang="scss">
.TheNav ul {
  display: flex;
  flex-flow: column nowrap;
  font-size: var(--step-2);
  font-weight: bolder;
  hyphens: manual;
  justify-content: space-around;
  list-style: none;
  min-height: 100vh;
  padding: var(--space-3xl) var(--space-l);
  text-align: center;
  text-transform: uppercase;

  a {
    display: inline-block;
    text-decoration: none;

    *.title {
      transform: skewX(0);
      transition: 0.05s;
    }
    *.author {
      transform: skewX(-15deg);
      transition: 0.05s ease-in-out;
    }

    &:active,
    &:hover {
      .title {
        animation: wiggle 1.3s linear alternate-reverse infinite;
      }
      .author {
        animation: wiggle 1s linear alternate infinite;
      }
    }
  }

  li + li {
    margin-top: var(--space-l);
  }
}
</style>
