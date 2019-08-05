<template>
  <a-container>
    <a-card style="margin-top: 20px; border: 0;">
      <div>
        <a-row type="flex" justify="space-around">
          <a-col :span="6">
            <a href="#">
              <h4>Selena</h4>
            </a>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente, animi.</p>
            <p>Email</p>
            <a-input type="email" style="width: 180px;" placeholder="example@gmail.com"></a-input>&nbsp;
            <a-button style="background: orange;">Subscribe</a-button>
            <br />
            <br />
            <br />
            <br />
            <p>&copy; Made with ♥ kai 2019</p>
          </a-col>
          <a-col :span="4">
            <h5>
              <a href="#">
                <b>Selena</b>
              </a>
            </h5>
            <p>Jurnal</p>
            <p>Tentang Kami</p>
            <p>Syarat Pengguna</p>
            <p>Kebijakan Privasi</p>
          </a-col>
          <a-col :span="4">
            <h5>
              <a href="#">
                <b>Partner</b>
              </a>
            </h5>
            <p>Become Seller</p>
            <p>Merchant</p>
            <p>Media Partner</p>
          </a-col>
          <a-col :span="4">
            <p>
              <a href="#">
                <b>Contact</b>
              </a>
            </p>
            <p>hello@selenago.com</p>
            <p>tlp/WA 08578787788</p>
            <br />
            <br />
            <br />
            <br />
            <br />
            <br />
            <H4 style="text-align: right;">
              <a-icon type="facebook" />&nbsp;
              <a-icon type="twitter" />&nbsp;
              <a-icon type="instagram" />&nbsp;
            </H4>
          </a-col>
        </a-row>
      </div>
    </a-card>
  </a-container>
</template>

<style scoped >
.card {
  background: white;
}
a {
  color: rgb(44, 44, 44);
}
</style>

