<script setup lang="ts">
import { plus } from '@han-river-front/utils';
import { BaseButton } from '@han-river-front/ui';
</script>

<template>
  <div>
    <p>{{ plus(1, 5) }}</p>
    <br />
    <BaseButton class="h-58 w-360"><p class="header-3">버튼</p></BaseButton>
    <br />
    <button class="w-600 bg-black text-white">버튼</button>
    <br />
    <!-- <button
      class="flex justify-center items-center text-white rounded-12 bg-black/85 cursor-pointer w-100"
      @click="$emit('click')"
    >
      <slot>asd</slot>
    </button> -->
  </div>
</template>
