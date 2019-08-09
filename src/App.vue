<template>
  <div id="app">
    <navbar></navbar>
    <br />
    <br />
    <div style="background-color: #F8F9FA;">
      <router-view />
      <br />
      <br />
    </div>
    <bawah />
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
import navbar from "@/components/Navbar.vue";
import bawah from "@/components/Bawah.vue";
import cardfix from "@/components/Cardfix.vue";

export default {
  components: {
    navbar,
    bawah,
    cardfix
  }
};
</script>
<style scoped>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
  /* text-align: center; */
  color: #2c3e50;
}
</style>
