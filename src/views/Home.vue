<template>
  <div>
    <div class="home">
      <br />
      <br />
      <tengah />
    </div>
    <sworkshop />
  </div>
</template>

<script>
import tengah from "@/components/Tengah.vue";
import isi from "@/components/Isi.vue";
import sworkshop from "@/components/Sworkshop.vue";

export default {
  name: "home",
  components: {
    tengah,
    isi,
    sworkshop
  }
};
</script>
