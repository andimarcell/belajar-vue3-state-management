<script setup lang="ts">
const { numbers } = defineProps(['numbers']);
</script>
<template>
    <div>
        <h1>Great Grand Child</h1>
        <p>Numbers: {{ numbers }}</p>
    </div>
</template>