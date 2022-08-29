<script setup>
import { ref } from "vue";

const selectedClass = ref("");
</script>

<template>
  <li class="w-full px-4 py-2"><slot /></li>
</template>

<style scoped></style>
