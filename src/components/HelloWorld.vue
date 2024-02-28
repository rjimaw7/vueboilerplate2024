<script setup lang="ts">
import { ref } from 'vue';

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
    <div class="flex justify-center items-center flex-col gap-4">
        <h1 class="text-2xl">{{ msg }}</h1>
        <!-- <button type="button" @click="count++">count is {{ count }}</button> -->
    </div>
</template>
