<script setup lang="ts">
defineEmits(['click']);
</script>

<template>
  <button
    class="flex justify-center items-center text-white rounded-12 bg-black/85 cursor-pointer"
    @click="$emit('click')"
  >
    <slot></slot>
  </button>
</template>
