<template>
  <div class="max-w-full">
    <Header />
      <slot/>
      <footer class="text-center text-sm">
        <p>Built by <a href="https://github.com/cguttweb" target="_blank" rel="noopener">Chloe <font-awesome :icon="['fab', 'github']" size="xs"  /></a> in {{ getFullYear() }}. Powered by <a href="https://gridsome.org/" target="_blank">Gridsome</a></p>
      </footer>
  </div>
</template>

<script>
import Header from '../components/TheHeader.vue'
export default {
  components: {
    Header
  },
  methods: {
    getFullYear(){
        return "2020" + "-"+new Date().getFullYear()
    }
  } 
}
</script>


<style>
body {
  background-color: rgba(226, 94, 6, 0.5);
  font-family: 'Open Sans', Arial, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  margin:0;
  padding:0;
}

</style>
