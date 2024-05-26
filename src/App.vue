<template>
  <div>
    <!-- <Vbind /> -->
    <Vmodel />
  </div>
</template>

<script>
import Vbind from "./components/Vbind.vue";
import Vmodel from "./components/Vmodel.vue";

export default {
  components: {
    Vbind,
    Vmodel
  },
  // data() {
  //   return {
  //     imageSrc: 'https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Red_Apple.jpg/1920px-Red_Apple.jpg'
  //   }
  // }
}
</script>
