<script setup>

defineProps({
  src: {
    type: String,
    required: true,
  },
  alt: {
    type: String,
    default: '',
  },
})

</script>

<template>
  <img :src="src" :alt="alt" class="rounded-t-full object-cover max-w-120 aspect-[4/5]" />
</template>
