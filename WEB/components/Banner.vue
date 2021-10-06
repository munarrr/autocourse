<template>

  <div>
      <ModalPopup v-show="showModal"  @close-modal="showModal = false"  />
    <section class="banner-section banner-one">
      <div class="left-based-text">
        <div class="base-inner">
          <div class="hours">
            <ul class="clearfix">
              <li><span>Пон - Суб</span></li>
              <li><span>9:00 - 17:00</span></li>
            </ul>
          </div>
          <div class="social-links">
            <ul class="clearfix">
              <li><a href="#"><span>Twitter</span></a></li>
              <li><a href="#"><span>Facebook</span></a></li>
              <li><a href="#"><span>Youtube</span></a></li>
            </ul>
          </div>
        </div>
      </div>

      <div class="banner-carousel">

        <no-ssr> <!-- important to add no-ssr-->
          <carousel :items="1">
        <!-- Slide Item -->
        <div class="slide-item">
          <div class="image-layer" style="background-image: url(/images/background/slide1.jpg);"></div>
          <div class="left-top-line"></div>
          <div class="right-bottom-curve"></div>
          <div class="right-top-curve"></div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">начни всего с 1000 СОМ!</div>
                  <h1>Получи права за 4 недели</h1>
                  <div class="link-box">
                  
                    <button @click="showModal = true" class="theme-btn btn-style-one" to="/about">
                      <i class="btn-curve"></i>
                      <span class="btn-title">Записаться</span>
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Slide Item -->
        <div class="slide-item">
          <div class="image-layer" style="background-image:url(/images/background/slide1.jpg);"></div>
          <div class="left-top-line"></div>
          <div class="right-bottom-curve"></div>
          <div class="right-top-curve"></div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">to Linoor agency</div>
                  <h1>Smart Web <br>Design Agency</h1>
                  <div class="link-box">
                    <nuxt-link class="theme-btn btn-style-one" to="/about">
                      <i class="btn-curve"></i>
                      <span class="btn-title">Discover More</span>
                    </nuxt-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

          </carousel>
        </no-ssr>

      </div>
    </section>

  </div>

</template>

<script>
import ModalPopup from "../components/ModalPopup";
  export default {
    name: "Banner",
    components:{ 
   ModalPopup
    },
    data(){
      return{
        showModal:false,
      }
    }
  }
</script>

<style scoped>

</style>
