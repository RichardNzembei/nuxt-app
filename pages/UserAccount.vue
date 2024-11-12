<script setup>
import { ref } from 'vue';
const count=ref(3)
</script>
<template>
    <div class="flex justify-center items-center mt-5">
        <UChip :text="count"  size="2xl">
      <UButton icon="i-heroicons-inbox" color="yellow" />
    </UChip>
    </div>
 
  </template>
  