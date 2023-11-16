<template>
  <div class="">
    <h4>Your Balance</h4>
    <h1 id="balance">${{ total }}</h1>
  </div>
</template>

<script setup>
const props = defineProps({
  total: {
    type: Number,
    required: true,
  },
});
</script>
