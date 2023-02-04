<script setup lang="ts">
import { ref } from 'vue';
import WhiteTLogo from '/images/logos/logo-v1.png';
</script>

<template>
    <NuxtLink to="/" class="d-flex">
        <img :src="WhiteTLogo" alt="logo"/>
    </NuxtLink>
</template>