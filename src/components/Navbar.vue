<template>
  <div class="card">
    <b-navbar toggleable="lg" type="light" style="background-color: white;" class="fixed-top">
      <div class="container">
        <b-navbar-toggle target="nav-collapse">
          <h5>Selena</h5>
        </b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-brand href="#">NavBar</b-navbar-brand>

          <b-navbar-nav>
            <a-input placeholder="Cari aktifitas" class="sos">
              <a-icon slot="prefix" type="search" />
              <a-icon v-if="userName" slot="suffix" type="close-circle" @click="emitEmpty" />
            </a-input>
          </b-navbar-nav>

          <!-- Right aligned nav items -->

          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item href="#">About</b-nav-item>
              <b-nav-item href="#">Blog</b-nav-item>
              <b-nav-item href="#">Bantuan</b-nav-item>
              <popsign />
            </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>

<script>
import popsign from "./Popsign.vue";
export default {
  components: {
    popsign
  }
};
</script>

<style scoped>
@import url("//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css");
body {
  margin: 30px;
}
.search {
  position: relative;
  color: #aaa;
  font-size: 16px;
}

.search input {
  width: 250px;
  height: 32px;

  background: #fcfcfc;
  border: 1px solid #aaa;
  border-radius: 5px;
  box-shadow: 0 0 3px #ccc, 0 10px 15px #ebebeb inset;
}

.search input {
  text-indent: 32px;
}
.search .fa-search {
  position: absolute;
  top: 10px;
  left: 10px;
}
input.sos,
textarea {
  background: cyan;
}
</style>