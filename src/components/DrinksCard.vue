<template>
<!-- <div class="max-w-sm lg:w-4/5"> -->
    <div class="w-4/5 text-center rounded shadow-lg">
    <img class="w-full" :src="coffee.photo" :alt="coffee.name">
        <div class="px-6 py-4">
            <h2 class="font-bold mb-2 text-lg uppercase">{{ coffee.name }}</h2>
            <p class="text-gray-800 text-base">
            {{ coffee.description }}
            </p>
            <p class="text-gray-800 text-base">Type: {{ coffee.type }}</p>
        </div>
    </div>
<!-- </div> -->
</template>

<script>
    export default {
        props: ['coffee']
    }
</script>
