<template>
  <a-container>
    <a-card>
      <div>
        <a-card-meta title="Andrea May" description="★ 4.0" style="padding: 10px; border: 0;">
          <a-avatar
            href="#"
            :size="60"
            slot="avatar"
            src="https://img.pngio.com/parent-directory-avatar-2png-avatar-png-256_256.png"
            description="budi doremis"
          />
        </a-card-meta>
        <a-card style="margin-left: 85px; border: 0;">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex asperiores laborum molestias eius, ipsam est neque non aperiam, reprehenderit iure repellendus sapiente esse quibusdam unde dolore praesentium dolor explicabo. Molestiae?</p>
        </a-card>
      </div>
    </a-card>
    <br />
    <a-card>
      <div>
        <a-card-meta title="Andrea May" description="★ 4.0" style="padding: 10px; border: 0;">
          <a-avatar
            :size="60"
            slot="avatar"
            src="https://img.pngio.com/parent-directory-avatar-2png-avatar-png-256_256.png"
            description="budi doremis"
          />
        </a-card-meta>
        <a-card style="margin-left: 85px; padding: 1px; border: 0;">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex asperiores laborum molestias eius, ipsam est neque non aperiam, reprehenderit iure repellendus sapiente esse quibusdam unde dolore praesentium dolor explicabo. Molestiae?</p>
        </a-card>
      </div>
    </a-card>

    <br />
    <a-card>
      <div>
        <a-card-meta title="Andrea May" description="★ 4.0" style="padding: 10px;">
          <a-avatar
            :size="60"
            slot="avatar"
            src="https://img.pngio.com/parent-directory-avatar-2png-avatar-png-256_256.png"
          />
        </a-card-meta>
        <a-card style="margin-left: 85px; padding: 1px; border: 0;">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex asperiores laborum molestias eius, ipsam est neque non aperiam, reprehenderit iure repellendus sapiente esse quibusdam unde dolore praesentium dolor explicabo. Molestiae?</p>
        </a-card>
      </div>
    </a-card>
    <br />
    <a href="#">
      Lihat Selengkapnya
      &nbsp;
      <b>></b>
    </a>
  </a-container>
</template>

<script>
import rate from "./Rate.vue";
export default {
  components: {
    rate
  }
};
</script>

<style scoped>
.ant-card-body {
  padding: 0px;
  border: none;
}
.a-card-meta {
  border: 0;
}
.description {
  color: gold;
  background: gold;
}
.card-meta {
  color: gold;
  border: none;
}
</style>
