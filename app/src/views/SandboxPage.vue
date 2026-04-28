<script setup lang="ts">
import BaseTextInput from '@/components/BaseTextInput.vue'
import { ref } from 'vue'

const firstName = ref('')
</script>

<template>
  <h1>Sandbox Page</h1>
  <p>{{ firstName }}</p>
  <BaseTextInput
    id="first-name"
    label="First name"
    placeholder="My Test placholder"
    v-model="firstName"
  />
</template>

<style scoped></style>
