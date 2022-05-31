<template>
  <main>
    <JumbotronComponent/>
    
    <div class="featured d-flex debug h300">featured
      <div class="container debug">
        <div class="debug h50 d-flex justify-content-center">titolo</div>
        <div class="debug h50 d-flex justify-content-center">bottoni</div>
        <div class="debug h100">card</div>
      </div>
    </div>

    <div class="collection debug h300">
      <div class="row">
        <div class="col debug h300">winter</div>
        <div class="col debug h300">spring</div>
        <div class="col debug h300">autumn</div>
      </div>
    </div>

    <div class="best-seller debug h200">
      <div class="container debug">
        <div class="debug h50 d-flex justify-content-center">best-seller</div>
        <div class="debug h100 d-flex justify-content-center">card a scorrimento</div>
      </div>
    </div>

    <div class="offerte debug h200">
      <div class="container debug">
        <div class="row justify-content-around align-items-center">
          <div class="col-4 debug h100">70</div>
          <div class="col-4 debug h100">free</div>
        </div>
      </div>
    </div>

    <div class="new-arrivals debug h300">
      <div class="debug h100 d-flex justify-content-center">nuovi arrivi</div>
      <div class="debug h200">card a scorrimento</div>
    </div>

    <div class="testimonials debug h300">
      <div class="foto-test debug h50 d-flex justify-content-center align-items-center">foto</div>
      <div class="testimonianza debug h100 d-flex justify-content-center align-items-center">testimonianza</div>
      <div class="tondini debug h50 d-flex justify-content-center align-items-center">O O</div>
    </div>

    <div class="our-blog debug h300">
      <div class="container">
        <div class="debug h50 d-flex justify-content-center align-items-center">from our blog</div>
        <div class="debug h200">
          <div class="row">
            <div class="col debug h200">
              <div class="foto-blog debug h100">foto</div>
              <div class="testo-blog debug h50">testo</div>
            </div>
            <div class="col debug h200">
              <div class="foto-blog debug h100">foto</div>
              <div class="testo-blog debug h50">testo</div>
            </div>
            <div class="col debug h200">
              <div class="foto-blog debug h100">foto</div>
              <div class="testo-blog debug h50">testo</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="sunto-colonne debug h300">
      <div class="container debug">
        <div class="row">
          <div class="col debug h200">featured</div>
          <div class="col debug h200">on sale</div>
          <div class="col debug h200">top rated</div>
          <div class="col debug h200">latest reviews</div>
        </div>
      </div>
    </div>

  </main>
</template>

<script>
import JumbotronComponent from './JumbotronComponent.vue';
export default {
    name: "MainComponent",
    components: { JumbotronComponent }
}
</script>

<style lang="scss" scoped>
@import "../assets/style/_general.scss"
</style>