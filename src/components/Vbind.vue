<template>
  <div>
    <img 
      v-bind:src="imageSrc" 
      v-bind:width="imageWidth" 
      v-bind:height="imageHeight" 
      alt="Apple"
    >
  </div>
</template>

<script>
export default {
  data() {
    return {
      imageSrc: 'https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Red_Apple.jpg/1920px-Red_Apple.jpg',
      imageWidth: '300px', 
      imageHeight: '300px' 
    }
  }
}
</script>
