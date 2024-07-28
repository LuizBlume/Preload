<script setup>
import { ref } from 'vue';
const loading = ref(true);
</script>
<template>
    <div class="container">
        <div class="box-load" v-if="loading">
            <div class="preload"></div>
        </div>
    </div>
</template>
<style scoped>
@import '../assets/style.css';
</style>