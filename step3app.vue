<script>
export default {
  data () {
    return {
      titleClass: 'title' // returns the style color for whatever title means
    }
  }
}
</script>

<template>
  <!--v binds the style linked to titleClass through the .title class below in <style>  -->
  <h1 :class="titleClass" > Make me red </h1>
</template>

<style>
  .title {
    color:red;
  }
</style>
// 