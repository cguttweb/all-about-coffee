<template>
    <div class="" tabindex="0">
        <h2 class="capitalize font-bold text-xl">{{ name }}</h2>
        <p class="px-4 py-2 text-center text-gray-800 h-36">
        {{ description }}
        </p>
    </div>
</template>

<script>
    export default {
        props: ['name', 'description']
    }
</script>

<style scoped>

</style>