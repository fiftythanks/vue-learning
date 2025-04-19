<script setup>
import { defineProps } from 'vue';

defineProps({
  bg: {
    types: String,
    default: 'bg-gray-100',
  },
});
</script>

<template>
  <div :class="`${bg} rounded-lg p-6 shadow-md`">
    <slot></slot>
  </div>
</template>
