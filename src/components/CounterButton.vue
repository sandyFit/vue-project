<script setup>
import { ref } from 'vue';

const count = ref(0)
</script>


<template>
    <button @click="count++">You clicked me {{ count }} times.</button>

</template>

<style>
    button {
        width: 20rem;
        padding: 1rem 2rem;
        font-size: 1rem;
        text-transform: uppercase;
        border-radius: 4px;
    }
</style>