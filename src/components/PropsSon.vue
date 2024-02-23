<template>
    <h1>Son</h1>
</template>
<script setup lang="ts">
import { inject } from 'vue';
const appMsg = inject('app-msg');
console.log("🚀 ~ appMsg:", appMsg)
</script>