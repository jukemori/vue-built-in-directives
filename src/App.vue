<template>
  <div>
    <!-- <Vbind /> -->
    <!-- <Vmodel /> -->
    <!-- <Vif /> -->
    <Vfor />
  </div>
</template>

<script>
import Vbind from "./components/Vbind.vue";
import Vmodel from "./components/Vmodel.vue";
import Vif from "./components/Vif.vue";
import Vfor from "./components/Vfor.vue";

export default {
  components: {
    Vbind,
    Vmodel,
    Vif,
    Vfor
  },
}
</script>
