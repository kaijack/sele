<template>
  <div>
    <card>
      <!-- <a-avatar style="backgroundColor:#87d068" icon="user" /> -->

      <a-card-meta title="Oleh" description="Nara Tour Organizer">
        <a-avatar
          slot="avatar"
          :size="60"
          src="https://img.pngio.com/parent-directory-avatar-2png-avatar-png-256_256.png"
        />
      </a-card-meta>
      <br />
      <div>
        <!-- <b-table striped hover :items="jadwal"></b-table> -->
        <h5>Deskripsi</h5>
        <p>
          <span v-html="info.description"></span>
        </p>
        <br />
        <br />
        <h5>Lokasi</h5>
        <div style="color: grey">{{ info.address}}</div>
        <br />
        {{ info.detail_address}}
        <br />
        <br />
        <div>
          <a-button type="primary" icon="environment" ghost>Lihat di Google Map</a-button>
        </div>
        <br />
        <br />
        <div style="color: grey">
          <h5>Detail Aktifitas</h5>
          <br />
          <p>
            <span v-html="info.notes"></span>
          </p>
        </div>
      </div>
      <hr />
      <h4>What to bring</h4>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur officiis veniam commodi quod consequuntur.</p>
      <hr />
      <h4>What I'll provide</h4>
      <a-icon type="check" />&nbsp; asd
      <br />
      <a-icon type="check" />&nbsp; ddd
      <br />
      <a-icon type="check" />&nbsp; asdd
      <br />
      <a-icon type="check" />&nbsp; sksk
      <hr />
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3952.722843049921!2d110.36788121450007!3d-7.819133279816312!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e7a57b160cf54dd%3A0xbc674abd262e610a!2sARKADIA!5e0!3m2!1sen!2sid!4v1564782000317!5m2!1sen!2sid"
        width="100%"
        height="360"
        frameborder="0"
        style="border:0"
        allowfullscreen
      ></iframe>
      <hr />
      <h5>
        <a style="color: black;" href="#">Rating & Review</a>
      </h5>
      <rate />
      <br />
      <comments />
      <hr />
      <div></div>
    </card>
  </div>
</template>

<script>
import axios from "axios";

import comments from "./Comments";
import rate from "./Rate";
export default {
  components: {
    comments,
    rate
  },
  data() {
    return {
      info: []
    };
  },
  mounted() {
    axios
      .get(
        "https://dev-api.selenago.com/api/v1/activity/sunrise-merapi-lava-tour143642"
      )
      .then(response => (this.info = response.data.data));
    this.info = data.notes;
    this.info = data.address;
    this.info = data.detail_address;

    console.log(info);
  }
};
</script>

<style scoped>
.col {
  display: inline-block;
}
.col.mid {
  vertical-align: middle;
}
.people {
  display: inline-block;
  width: 33%;
  margin-bottom: 40px;
}

.image-list {
  display: inline-block;
  vertical-align: middle;
}

.image-list ul {
  padding: 0 0 0 30px;
  margin: 0;
  list-style: none;
}
</style>
