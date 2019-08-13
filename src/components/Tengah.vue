<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-8 col -sm-8">
        <corousal />
        <br />
        <isi />
        <!-- <sworkshop/> -->
      </div>
      <div class="col-xs-4 col-sm-4 activity-schedule-display d-none d-sm-block">
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
.collapsed > .when-opened,
:not(.collapsed) > .when-closed {
  display: none;
}
</style>