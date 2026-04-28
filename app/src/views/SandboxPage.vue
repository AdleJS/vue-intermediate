<script setup lang="ts">
import SlotDemo from '@/components/SlotDemo.vue'
</script>

<template>
  <h1>Sandbox Page</h1>
  <SlotDemo>
    <template v-slot:default="slotProps">
      <p>{{ slotProps.count }}</p>
    </template>
    <template v-slot:footer>
      <p>This is my footer content</p>
    </template>
  </SlotDemo>
</template>

<style scoped></style>
