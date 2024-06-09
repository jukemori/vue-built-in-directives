<template>
  <div>
    <!-- <Vbind /> -->
    <!-- <Vmodel /> -->
    <!-- <Vif /> -->
    <!-- <Vfor /> -->
    <Vshow />
  </div>
</template>

<script>
import Vbind from "./components/Vbind.vue";
import Vmodel from "./components/Vmodel.vue";
import Vif from "./components/Vif.vue";
import Vfor from "./components/Vfor.vue";
import Vshow from "./components/Vshow.vue";

export default {
  components: {
    Vbind,
    Vmodel,
    Vif,
    Vfor,
    Vshow,
  },
}
</script>
