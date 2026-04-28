<script setup lang="ts">
import GreatGrantChild from './GreatGrantChild.vue';
const { numbers } = defineProps(['numbers']);


</script>

<template>
    <div>
        <h1>Grand Child</h1>
        <div class="line"></div>
        <GreatGrantChild :numbers="numbers"/>
    </div>
</template>