<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-8">
        <corousal />
        <br />
        <isi />
        <!-- <sworkshop/> -->
      </div>
      <div class="col-sm-4 activity-schedule-display">
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



<style scoped>
.activity-schedule-display {
    display: block;
}

.col-sm-4 {
    position: relative;
    width: 100%;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;
}
</style>