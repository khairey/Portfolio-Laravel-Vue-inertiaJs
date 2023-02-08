<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Frontend from '@/Layouts/Frontend.vue'

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    <Head title="Welcome to Portoflio" />
    <Frontend></Frontend>
</template>
