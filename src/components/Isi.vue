<template>
  <div>
    <card>
      <!-- <a-avatar style="backgroundColor:#87d068" icon="user" /> -->

      <a-card-meta title="Host by:" description="Katherine">
        <a-avatar
          slot="avatar"
          :size="60"
          src="https://img.pngio.com/parent-directory-avatar-2png-avatar-png-256_256.png"
        />
      </a-card-meta>
      <br />
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam esse officia ratione possimus voluptate officiis harum qui libero eveniet, repudiandae quidem voluptatum sequi recusandae, aperiam ipsam accusantium a vitae eum nam ipsum ullam, at nostrum omnis! Rerum eum atque fugiat unde consequuntur magni assumenda omnis, laudantium quod illum maxime aspernatur.</p>
      <hr />
      <h4>Lorem ipsum dolor sit?</h4>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure voluptatum assumenda illo quod ipsam nihil, culpa ex consequuntur doloremque, reprehenderit officiis dolore consequatur placeat architecto in accusantium tempore distinctio porro sunt accusamus dolorum tempora nisi facilis. Laboriosam numquam quia accusamus soluta deserunt quibusdam aspernatur obcaecati
        <a
          href="#"
        >Lihat selengkapnya ></a>
      </p>
      <hr />
      <h4>Lorem ipsum</h4>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Molestias minima quam tempora aut reiciendis optio tempore eveniet ipsa. Exercitationem vel animi consectetur porro! Eaque fugiat sapiente veniam esse enim ipsum assumenda cumque dignissimos magnam hic.
        <a
          href="#"
        >Lihat selengkapnya!</a>
      </p>
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
import comments from "./Comments";
import rate from "./Rate";
export default {
  components: {
    comments,
    rate
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
