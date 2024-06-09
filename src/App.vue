<template>
  <div>
    <!-- <Vbind /> -->
    <!-- <Vmodel /> -->
    <!-- <Vif /> -->
    <!-- <Vfor /> -->
    <!-- <Vshow /> -->
    <!-- <Von /> -->
     <Vhtml />
  </div>
</template>

<script>
import Vbind from "./components/Vbind.vue";
import Vmodel from "./components/Vmodel.vue";
import Vif from "./components/Vif.vue";
import Vfor from "./components/Vfor.vue";
import Vshow from "./components/Vshow.vue";
import Von from "./components/Von.vue";
import Vhtml from "./components/Vhtml.vue";

export default {
  components: {
    Vbind,
    Vmodel,
    Vif,
    Vfor,
    Vshow,
    Von,
    Vhtml,
  },
}
</script>
