<script setup>

const props = defineProps({
  record: Object,
})


</script>

<template>
Name: {{ props.record.name }}
Description: {{ props.record.descriptions }}
</template>