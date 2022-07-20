<script setup>
// "props' is assigned a value but never used"
const props = defineProps({
  msg: String,
});
</script>

<template>
  <h2>{{ msg }}</h2>
  <!-- This would work -->
  <!-- <h2>{{ props.msg  }}</h2> -->
</template>
