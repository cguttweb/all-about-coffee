<template>
  <div class="layout">
    <Header />
      <slot/>
    <Footer />
  </div>
</template>

<script>
import Header from '../components/TheHeader'
import Footer from '../components/TheFooter'

export default {
  components: {
    Header,
    Footer
  }  
}
</script>


<style>
body {
  background-color: rgba(226, 94, 6, 0.5);
  font-family: 'Open Sans', Arial, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  margin: 0;
  padding: 0;
}


/* header, 
footer {
  @apply bg-orange-800;
  @apply text-white;
  @apply px-8;
  @apply py-2;
} */

/* h1 {
  @apply text-3xl;
  @apply text-center;
  @apply font-semibold;
  @apply py-3;
} */

/* h2 {
  @apply text-2xl;
  @apply text-center;
} */
/* 
main {
  @apply px-8;
  @apply py-4;
} */

a:hover {
  font-weight: bold;
  text-decoration: underline;
}
</style>
