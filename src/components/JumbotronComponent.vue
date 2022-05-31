<template>
  <div class="jumbotron d-flex justify-content-center align-items-center">
    <div class="text-center">
      <h1>Brand new arrivals</h1>
      <h5>new collection from new york</h5>
      <div class="d-flex justify-content-center">
        <button type="button" class="btn btn-outline-light cg-btn">View all</button>
        <button type="button" class="btn btn-outline-light cg-btn">Lookbook</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "JumbotronComponent"
}
</script>

<style lang="scss" scoped>
@import "../assets/style/_general.scss";

.jumbotron{
  height: 80vh;
  color:White;
  background-image: url(../assets/img/images/home1_slide_three_bg_2.jpg );
  background-size: cover;
  h1{
    text-transform: capitalize;
    font-size: 80px;
  }
  h5{
    text-transform: uppercase;
  }
  .cg-btn{
     border-radius: 20px !important;
      padding: 5px 10px 5px 10px;
      margin-right: 6px;
      font-size: 15px;
      text-transform: uppercase;
  }
}

</style>