<script setup>
const message=()=>{
  alert('hello')
}
</script>
<template>
  <div>
    <UButton 
    icon="i-heroicons-pencil-square"
    color="red"
    @click="message"
    >Actions</UButton>
  </div>
</template>