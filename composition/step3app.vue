<script setup>
import { ref } from 'vue' //import ref is "import"-tant Haaa

const titleClass = ref('title')
</script>

<template>
  <h1 :class="titleClass">Make me red</h1> 
</template>

<style>
.title {
  color: red;
}
</style>