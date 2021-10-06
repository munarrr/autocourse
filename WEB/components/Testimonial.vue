<template>
  <section class="testimonials-section">
    <div class="auto-container">
      <div class="sec-title">
        <h2>Customer feedbacks <span class="dot">.</span></h2>
      </div>
      <div class="carousel-box">
        <div class="testimonials-carousel">
          <carousel :autoplay="true" :margin="30" :responsive="{0: {items: 1},600: {items: 1},768: {items: 1},992: {items: 2},1200: {items: 2}}">
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-1.jpg"
                                                            alt=""></a></div>
                <div class="name">Shirley Smith</div>
                <div class="designation">Director</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-2.jpg"
                                                            alt=""></a></div>
                <div class="name">Mike hardson</div>
                <div class="designation">Director</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-3.jpg"
                                                            alt=""></a></div>
                <div class="name">Sarah albert</div>
                <div class="designation">Director</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-1.jpg"
                                                            alt=""></a></div>
                <div class="name">Shirley Smith</div>
                <div class="designation">Director</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-2.jpg"
                                                            alt=""></a></div>
                <div class="name">Mike hardson</div>
                <div class="designation">Director</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          <div class="testi-block">
            <div class="inner">
              <div class="icon"><span>“</span></div>
              <div class="info">
                <div class="image"><a href="/team"><img src="/images/resource/author-3.jpg"
                                                            alt=""></a></div>
                <div class="name">Sarah albert</div>
                <div class="designation">Director</div>
              </div>
              <div class="text">There are many variations of passages of lorem ipsum available but the
                majority have suffered alteration in some form, by injected humour, or randomised
                words which don't look even slightly believable.</div>
            </div>
          </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Testimonial"
    }
</script>

<style scoped>

</style>
