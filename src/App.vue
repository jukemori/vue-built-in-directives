<template>
  <div>
    <!-- <Vbind /> -->
    <!-- <Vmodel /> -->
    <Vif />
  </div>
</template>

<script>
import Vbind from "./components/Vbind.vue";
import Vmodel from "./components/Vmodel.vue";
import Vif from "./components/Vif.vue";

export default {
  components: {
    Vbind,
    Vmodel,
    Vif,
  },
}
</script>
