<script setup>
 const props = defineProps({
    name: String,
    handle: String
 })
</script>

<template>
    <div class="user">
        <span class="name"> {{ name }}</span>
        <span class="handle"> {{ handle }}</span>
    </div>
</template>

<style>
</style>