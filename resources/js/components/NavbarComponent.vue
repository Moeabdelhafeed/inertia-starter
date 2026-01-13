<template>
    <div class="w-full h-16 bg-slate-900 p-5 flex items-center justify-center gap-5">
        <Link :href="route('home')">Home</Link>
        <Link :href="route('about')">About</Link>
    </div>

</template>
<script setup>
import { Link } from '@inertiajs/vue3';


</script>
<style scoped>
    
</style>
