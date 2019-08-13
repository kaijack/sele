<template>
  <div>
    <div>
      <div class="home">
        <br />
        <br />
        <tengah />
      </div>
      <sworkshop />
    </div>
    <!-- <bawah /> -->
    <div class=".hidden-sm-up d-block d-sm-none">
      <b-button
        v-b-toggle.collapse-1
        variant="warning"
        class="fixed-bottom btn-block"
      >Pesan Sekarang</b-button>
      <b-collapse id="collapse-1" class="mt-2 mr-10 fixed-top">
        <cardfix />
      </b-collapse>
    </div>
  </div>
</template>

<script>
import tengah from "@/components/Tengah.vue";
import isi from "@/components/Isi.vue";
import sworkshop from "@/components/Sworkshop.vue";
import bawah from "@/components/Bawah.vue";
import cardfix from "@/components/Cardfix.vue";

export default {
  name: "home",
  components: {
    tengah,
    isi,
    sworkshop,
    bawah,
    cardfix
  }
};
</script>
