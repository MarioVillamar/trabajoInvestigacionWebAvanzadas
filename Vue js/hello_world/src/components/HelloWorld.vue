<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h2>Hola mundo desde Vue js</h2>
  <p>Autor: Mario Villamar </p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
