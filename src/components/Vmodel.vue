<template>
  <div>
    <input v-model="message" placeholder="Type a message">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: ''
    }
  }
}
</script>
