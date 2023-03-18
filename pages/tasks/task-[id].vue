<template>
    <div>
        Go Back
        <NuxtLink to="/tasks">Tasks</NuxtLink>
        <br>
        Task {{ $route.params.id }}]
    </div>
</template>

<script setup>

const route = useRoute()

console.log(route.params)

</script>

