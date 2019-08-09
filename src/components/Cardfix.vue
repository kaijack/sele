<template>
  <div class="schedule-card">
    <div>
      <b>
        Pesan Sekarang Juga!
        <br />
        <span style="font-size: 18px;">Rp200.000</span>
      </b>/pax
    </div>
    <hr />
    <div>
      <b>Tanggal Tersedia</b>
      <br />
      <br />
      <a-dropdown>
        <a-menu slot="overlay" @click="handleMenuClick">
          <a-menu-item key="1">Sabtu, 14 Juni - 15.00</a-menu-item>
          <a-menu-item key="2">Sabtu, 28 Juni - 15.00</a-menu-item>
          <a-menu-item key="3">Sabtu, 03 Agustus - 15.00</a-menu-item>
        </a-menu>
        <a-button block>
          <a style="float: left">Sabtu, 21 Juni - 15.00</a>
          <a-icon type="down" style="float: right;" />
        </a-button>
      </a-dropdown>
      <br />
    </div>
    <div>
      <br />
      <b>Jumlah yang ikut</b>
      <br />

      <div class="container">
        <div class="row">
          <div class="col-5">
            <a-button style="text-align: left; width: 130px; ">2 orang</a-button>&nbsp;
          </div>
          <div class="col-2" style="margin-left: 40px;">
            <a-button style="background: #D9D9E3;">
              <a-icon type="minus" style="padding-bottom: 6px; color: black;" />
            </a-button>
          </div>&nbsp;
          <div class="col-2" style="margin-left: 10px;">
            <a-button style="background: #FFA500;">
              <a-icon type="plus" style="padding-bottom: 6px; color: black;" />
            </a-button>
          </div>
        </div>
      </div>
      <hr />
      <div>
        Total
        <br />
        <b>Rp400.000</b>
        <br />
        <br />
        <div class="text-center">
          <a-button style="background: #FFA500" block>Pesan Sekarang</a-button>
          <br />
          <a href="#" style="color: orange">Punya kode promo?</a>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  methods: {
    change(affixed) {
      console.log(affixed);
    }
  }
};
</script>

<style scoped>
@import url("//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css");

.schedule-card {
  width: 100%;
  position: sticky;
  top: 75px;
  border-radius: 4px;
  background-color: #fff;
  box-shadow: 0 5px 18px 0 rgba(227, 123, 40, 0.1);
  padding: 50px;
  margin-bottom: 75px;
}
</style>