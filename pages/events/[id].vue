<script setup>
const nuxt = useNuxtApp()
console.log('nuxt',nuxt);
// const route = useRoute();
// console.log("route",route );

</script>

<template>
    <div>
        event Id: {{  $route.params.id }}
    </div>
</template>