<template>
  <div class="container">
    <div class="row no-gutters">
      <div class="col-12 col-sm-6 col-md-8">
        <corousal />
        <br />
        <isi />
        <!-- <sworkshop/> -->
      </div>
      <div class="col-6 col-md-4">
        <cardfix />
      </div>
    </div>
  </div>
</template>

<script>
import cardfix from "./Cardfix.vue";
import corousal from "./Corousal.vue";
import isi from "./Isi.vue";
// import sworkshop from "./Sworkshop.vue";

export default {
  components: {
    corousal,
    cardfix,
    isi
    // sworkshop
  }
};
</script>



