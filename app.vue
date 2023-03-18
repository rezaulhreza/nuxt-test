<template>
  <div>
    <NuxtLayout :layout="layout">
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
const layout = "default"; //why? choose this based on an API call or logged-in status
</script>



