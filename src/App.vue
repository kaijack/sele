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
  </div>
</template>


<script>
import navbar from "@/components/Navbar.vue";
import bawah from "@/components/Bawah.vue";

export default {
  components: {
    navbar,
    bawah
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
