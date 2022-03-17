<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++ 
      //The component instance exposes the data properties declared by data.
    }
  }
}
</script>

<template>
  <!-- uses v-on shortcut @ -->
  <!--  -->
  <button @click="increment">count is: {{ count }}</button>
</template>