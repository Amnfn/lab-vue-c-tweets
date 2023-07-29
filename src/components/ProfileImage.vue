<script setup>
const props = defineProps({
    image: String,
});
</script>

<template>
    <img :src="image" alt="profile" class="profile"/>
</template>

<style>
</style>