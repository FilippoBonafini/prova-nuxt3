<script setup>
const route = useRoute()
useHead({
    title: `Cars in ${route.params.city}`
})
definePageMeta({
    layout: 'custom',
})
</script>


<template>
    <div class="mt-32 flex">
        <CarSideBar />
        <NuxtPage />
    </div>
</template>