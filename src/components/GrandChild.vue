<script setup lang="ts">
import GreatGrantChild from './GreatGrantChild.vue';
import useNumbers from '@/composables/useNumbers';

const { numbers, addNumber } = useNumbers();
</script>

<template>
    <div>
        <h1>Grand Child</h1>
        {{ numbers }}
        <div class="line"></div>
        <GreatGrantChild/>
    </div>
</template>