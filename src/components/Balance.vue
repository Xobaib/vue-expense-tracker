<template>
  <h4>Your Balance</h4>
  <h1 id="balance">${{ total.toFixed(2) }}</h1>
</template>

<script setup>
const props = defineProps({
  total: Number,
});
</script>
