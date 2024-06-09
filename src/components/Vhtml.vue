<template>
  <div v-html="htmlContent"></div>
</template>

<script>
export default {
  data() {
    return {
      htmlContent: '<p>This is <strong>HTML</strong></p>'
    }
  }
}
</script>
