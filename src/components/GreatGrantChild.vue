<script setup lang="ts">
// import { inject } from 'vue';
import { useNumbers } from '@/stores/numbers';

const { numbers, filterNumbers } = useNumbers();
// const numbers = inject('numbers');
</script>
<template>
    <div>
        <h1>Great Grand Child</h1>
        {{ filterNumbers(13) }}
    </div>
</template>