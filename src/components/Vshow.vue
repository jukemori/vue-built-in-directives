<template>
  <div>
    <p v-show="isVisible">This is visible</p>
    <button @click="isVisible = !isVisible">Toggle Visibility</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isVisible: true
    }
  }
}
</script>
