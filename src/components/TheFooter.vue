<template>
    <div>
        <!-- <footer class="text-center text-sm"> -->
        <footer class="text-center text-sm md:absolute bottom-0 left-0 right-0 py-2">
            <p>Built by <a href="https://github.com/cguttweb" target="_blank" rel="noopener">Chloe<font-awesome :icon="['fab', 'github']" size="xs"  /></a> in {{ getFullYear() }}. Powered by <a href="https://gridsome.org/" target="_blank">Gridsome</a></p>
        </footer>
    </div>
</template>

<script>
    export default {
        methods: {
            getFullYear(){
                return "2020 - " + new Date().getFullYear()
            }
        }
    }
</script>

<style scoped>
footer {
  background-color: rgba(194, 82, 8, 0.75);
  position: absolute;
  bottom: 0;
  width: 100%;
}

a {
    color: rgba(255, 255, 255, 1);
    font-weight: bold;
}

p {
    margin: 0;
}
</style>