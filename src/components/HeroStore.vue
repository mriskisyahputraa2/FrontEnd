<template>
      <!-- Hero Section Begin -->
    <section class="hero-section">
      <!-- carousel -->
      <carousel class="hero-items" :items="1" :nav="false"> <!--secara default item yang ditampilkan adalah 3, disini di modif yang ditampilkan 1, supaya bisa ada slide gambar. dan secara default juga akan menampilkan sebuah navbar, untuk menghilangkannya membuat navbar nya menjadi false-->
        <div class="single-hero-items set-bg" style="background-image:url('/img/hero-1.jpg');">
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Bag,kids</span>
                <h1>Black friday</h1>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div class="single-hero-items set-bg" style="background-image:url('/img/hero-2.jpg');">
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Bag,kids</span>
                <h1>Black friday</h1>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div class="single-hero-items set-bg" style="background-image:url('/img/hero-3.jpg');">
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Bag,kids</span>
                <h1>Black friday</h1>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
      </carousel>
    </section>
    <!-- Hero Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";
export default {
    name: 'HeroStore',
    components:{
    carousel
  } 
}
</script>

<style>

</style>