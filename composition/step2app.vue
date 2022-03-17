<script setup>
import { reactive } from 'vue'
import {ref} from 'vue'

  const state = reactive ({
    count: 0
  })
  function increment(){
    state.count++
  }
  
  const message = ref('Hello World!')
// component logic
</script>

<template>
  <div>
    <h1>{{ message }}</h1>
    <p> count is: {{ state.count }}</p>
		<button @click="increment"> {{ state.count }}</button>
  </div>
</template>