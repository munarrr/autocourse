<template>
  <section class="facts-section">
    <div class="image-layer" style="background-image: url(/images/background/44.jpg;"></div>
    <div class="auto-container">
      <div class="inner-container">

        <!-- Fact Counter -->
        <div class="fact-counter" v-observe-visibility="onVisibilityChange">
          <div class="row clearfix">

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 100 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title">уже получили свою праву</div>
                </div>
              </div>
            </div>

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box alternate">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 7 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title"> инструкторов</div>
                </div>
              </div>
            </div>

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 12 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title">лет</div>
                </div>
              </div>
            </div>

            <!--Column-->
            <div class="column counter-column col-lg-3 col-md-6 col-sm-12">
              <div class="inner">
                <div class="content">
                  <div class="count-outer count-box">
                    <span class="count-text"><countTo :startVal='0' :endVal='startCounter ? 27 : 0' :duration='3000'></countTo></span>
                  </div>
                  <div class="counter-title"> дней можешь получить права</div>
                </div>
              </div>
            </div>

          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
  import countTo from 'vue-count-to';
  import { ObserveVisibility } from 'vue-observe-visibility'

    export default {
      name: "FactSection",
      components: { countTo },
      directives: {
        ObserveVisibility
      },
      data() {
        return{
          startCounter: false
        }
      },
      methods: {
        onVisibilityChange (isVisible) {
          if (isVisible){
            this.startCounter = true;
          }

        },
      },
    }
</script>

<style scoped>

</style>
