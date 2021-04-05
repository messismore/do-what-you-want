<template>
  <header class="TheDWYW">
    <h1>
      <span class="do">Do</span> <span class="what">What</span>
      <span class="you">You</span> <span class="want"> Want</span>
    </h1>
    <div>
      <p>
        Ten Very Different Projects in an Unusual Semester at
        <span class="nowrap">Universität der Künste Berlin,</span> Winter 2020.
      </p>
      <p>
        <em>Do What You Want</em> is a recurring studio hosted by the
        <em>Chair for Design and Building Planning</em>.
      </p>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style lang="scss">
.TheDWYW {
  align-items: center;
  display: flex;
  flex-flow: column nowrap;
  justify-content: space-around;
  min-height: 100vh;
  padding: var(--space-s);

  h1 {
    font-size: var(--step-6);
    line-height: var(--step-6);
    text-align: center;
    text-transform: uppercase;
  }

  h1 * {
    display: block;
  }

  p {
    font-size: var(--step-0);
  }

  em {
    font-size: var(--step--1);
  }

  .do {
    animation: wiggle 5s linear alternate infinite;
  }

  .what {
    animation: wiggle 6s linear alternate-reverse infinite;
  }

  .you {
    animation: wiggle 4s linear alternate infinite;
  }

  .want {
    animation: wiggle 7s linear alternate-reverse infinite;
  }
}
</style>
