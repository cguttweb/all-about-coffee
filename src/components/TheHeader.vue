<template>
  <!-- <div> -->
    <header class="d-flex justify-content-center py-2">
      <nav role="navigation">
        <b-nav>
          <b-nav-item href="/">{{ $static.metadata.siteName }} &nbsp;<font-awesome :icon="['fa', 'coffee']" /></b-nav-item>
          <b-nav-item href="/">Home</b-nav-item>
          <b-nav-item href="/beans-and-grinds/">Beans and Grinds</b-nav-item>
          <b-nav-item href="/drinks/">Drinks</b-nav-item>
          <b-nav-item href="/flavourings/">Flavourings</b-nav-item>
          <b-nav-item href="/history/">History</b-nav-item>
          <b-nav-item href="/machines/">Machines</b-nav-item>
          <b-nav-item href="/glossary/">Glossary</b-nav-item>
          <b-nav-item href="/world-coffees/">World Coffees</b-nav-item>
        </b-nav>
      </nav>
    </header>
  <!-- </div> -->
</template>

<script>
export default {
    name: 'Header'
}
</script>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style scoped>
header {
  background-color: rgba(194, 82, 8, 0.75);
}

a {
  color: #ffffff;
  font-weight: bold;
  font-variant: small-caps;
}

a:hover {
  color: #ffffff;
  font-weight: bold;
}
</style>