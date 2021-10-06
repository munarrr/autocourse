<template>
  <section class="about-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Image Column-->
        <div class="image-column col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="image-block wow fadeInLeft" data-wow-delay="0ms" data-wow-duration="1500ms"><img
              src="/images/resource/about1.jpg" alt=""></div>
            <div class="image-block wow fadeInUp" data-wow-delay="300ms" data-wow-duration="1500ms"><img
              src="/images/resource/about2.jpg" alt=""></div>
          </div>
        </div>
        <!--Text Column-->
        <div class="text-column col-xl-6 col-lg-12 col-md-12 col-sm-12">
          <div class="inner">
            <div class="sec-title">
              <h2>Наш образовательный<br>центр <span class="dot">.</span></h2>
              <div class="lower-text">Автошкола УСТА работает с 2002 года. За прошедшие годы автошкола сумела накопить богатый опыт по подготовке водителей.</div>
            </div>
            <div class="text">
              <p>Вас пройти курс обучения по программе подготовки водителей транспортных средств:</p>
            </div>
            <div class="text clearfix">
              <ul>
                <li>категории А</li>
                <li>категории B</li>
                <li>категории C</li>
              </ul>
              <div class="since"><span class="txt">с <br>2008</span></div>
            </div>
            <div class="link-box">
              <nuxt-link class="theme-btn btn-style-one" to="/about">
                <i class="btn-curve"></i>
                <span class="btn-title">Записаться</span>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "About"
    }
</script>

<style scoped>

</style>
