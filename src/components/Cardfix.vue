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
      <a-select defaultValue="Sabtu, 21 Agustus 2019" style="width: 245px" @change="handleChange">
        <a-select-option value="Senin, 25 Agustus 2019">Senin, 25 Agustus 2019</a-select-option>
        <a-select-option value="Rabu, 27 Agustus 2019">Rabu, 27 Agustus 2019</a-select-option>
        <a-select-option value="Jumat, 29 Agustus 2019">Jumat, 29 Agustus 2019</a-select-option>
      </a-select>
      <br />
    </div>
    <div>
      <br />
      <br />
      <b>Jumlah yang ikut</b>
      <br />
      <br />

      <div>
        <div class="row">
          <div class="col-5">
            <a-button style="text-align: left; ">2 orang</a-button>&nbsp;
          </div>
          <div class="col-2" style="margin-left: 10px;">
            <a-button style="background: #D9D9E3;">
              <a-icon type="minus" style="padding-bottom: 6px; color: black;" />
            </a-button>
          </div>
          <div class="col-2">
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
  padding: 27px;
  margin-bottom: 75px;
}
</style>