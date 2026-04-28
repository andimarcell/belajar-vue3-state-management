<script setup lang="ts">
// import { inject } from 'vue';
import GrandChild from './GrandChild.vue';
import { useNumbers } from '@/stores/numbers';

const { numbers } = useNumbers();
// const numbers = inject('numbers');
</script>

<template>
    <div>
        <h1>Child</h1>
        {{ numbers }}
        <div class="line"></div>
        <GrandChild/>
    </div>
</template>