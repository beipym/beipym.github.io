<script setup >

import { ref } from 'vue'
const count = ref("bg-red-200")

</script>

<template>

    <SectionOneBase/>
    
</template>

<style scoped>
    .red{
        @apply bg-red-400;
    }
    .black{
        @apply bg-blue-600;
    }

</style>
  