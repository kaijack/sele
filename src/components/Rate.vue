<template>
  <div>
    <div class="rate-container">
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      &nbsp;
      <span>
        <a href="#" target="#">(20 Review)</a>
      </span>
    </div>
  </div>
</template>


<style scoped>
@import url("///netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css");
.rate-container > i {
  text-align: left;
  font-size: 20px;
}

.rate-container > i:hover,
.rate-container > i:hover ~ i {
  color: gold;
}
.fa-star {
  color: gold;
}
span a {
  color: rgb(207, 204, 204);
}
</style>
