<template>
  <Layout>
    <main class="home text-center">
      <h1 class="md:pb-8">All About Coffee  <font-awesome :icon="['fa', 'coffee']" /></h1>

        <p class="pb-3">This is a small project I've built with <a href="https://gridsome.org" target="_blank">Gridsome</a> a Vue-based Jamstack framework using <a href="https://getbootstrap.com/" target="_blank">bootstrap</a> for styling.</p>

        <p>Coffee is a personal addiction (obsession). The links above will give more information about particular aspects of brewing, roasting and making coffee.</p>
    </main>
  </Layout>
</template>

<script>

export default {
  metaInfo: {
    title: 'Home'
  },

}
</script>


<style scoped>
.home {
  transform: translateY(250px);
}

a {
  color: #5a0303;
  text-decoration: underline;
}

</style>
