<template>
  <div>
    <p v-if="type === 'A'">Type A</p>
    <p v-else-if="type === 'B'">Type B</p>
    <p v-else>Other Type</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      type: 'A'
    }
  }
}
</script>
