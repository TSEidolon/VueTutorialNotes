<script>
export default {
  data() {
    return {
      message: 'Hello World!'
    }
  }
}
</script>

<template>
  <div>
    <h1> {{message}}</h1> 
    <h1> {{message.split('').reverse().join("")}}</h1> <!-- split ('') breaks the string into pieces of 1 char. .reverse() reverses the split string. join('') joins the broken string -->
    <!-- !dlroW olleH -->
  </div>
</template>