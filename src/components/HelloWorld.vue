<script setup lang="ts">
defineProps<{ msg: string }>();
</script>

<template>
    <div class="flex justify-center items-center flex-col gap-4">
        <h1 class="text-2xl">{{ msg }}</h1>
    </div>
</template>
