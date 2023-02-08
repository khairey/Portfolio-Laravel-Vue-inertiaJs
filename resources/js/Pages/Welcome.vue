<script setup>
import { Head, Link } from '@inertiajs/vue3';
import Frontend from '@/Layouts/Frontend.vue'
import Hero from '@/Components/Frontend/Hero.vue'
import Promote from '@/Components/Frontend/Promote.vue'
import About from '@/Components/Frontend/About.vue'

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    <Head title="Welcome to Portoflio" />
    <Frontend>
        <Hero/>
        <Promote/>
        <About/>
    </Frontend>
</template>
