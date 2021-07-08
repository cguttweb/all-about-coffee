<template>
  <!-- <div> -->
    <header class="d-flex justify-content-center py-2">
    <!-- <b-nav-item class="hidden md:block text-center" to="/">{{ $static.metadata.siteName }} &nbsp;<font-awesome :icon="['fa', 'coffee']" /></g-b-nav-item> -->
      <nav role="navigation">
        <b-nav>
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
  background-color: rgba(226, 94, 6, 0.75);
}

a {
  color: #ffffff;
}

a:hover {
  color: #ffffff;
  font-weight: bold;
  text-decoration: none;
}
</style>