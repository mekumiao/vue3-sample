<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

/**
 * show message
 * @text context
 */
function showMessage(context: string) {
  alert(context);
}

showMessage("Di di di !!");
</script>

<template>
  <h1>{{ msg }}</h1>
</template>
