<template>
  <div>
    <v-row>
      <!-- Influencing The Influencer -->
      <v-col
        md="4"
        sm="6"
        cols="12"
      >
        <v-card>
          <v-img
            src="@/assets/images/pages/card-basic-influencer.png"
            height="250"
          />
          <v-card-title>
            Influencing The Influencer
          </v-card-title>
          <v-card-text>
            Cancun is back, better than ever! Over a hundred Mexico resorts have reopened and the state tourism minister predicts Cancun will draw as many visitors in 2006 as it did two years ago.
          </v-card-text>
        </v-card>
      </v-col>
     <v-col
        md="4"
        sm="6"
        cols="12"
      >
        <v-card>
          <v-img
            src="@/assets/images/pages/card-basic-influencer.png"
            height="250"
          />
          <v-card-title>
            Influencing The Influencer
          </v-card-title>
          <v-card-text>
            Cancun is back, better than ever! Over a hundred Mexico resorts have reopened and the state tourism minister predicts Cancun will draw as many visitors in 2006 as it did two years ago.
          </v-card-text>
        </v-card>
      </v-col>
       <v-col
        md="4"
        sm="6"
        cols="12"
      >
        <v-card>
          <v-img
            src="@/assets/images/pages/card-basic-influencer.png"
            height="250"
          />
          <v-card-title>
            Influencing The Influencer
          </v-card-title>
          <v-card-text>
            Cancun is back, better than ever! Over a hundred Mexico resorts have reopened and the state tourism minister predicts Cancun will draw as many visitors in 2006 as it did two years ago.
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import { ref } from '@vue/composition-api'

export default {
  setup() {
    const isCardDetailsVisible = false
    const rating = ref(5)

    return {
      isCardDetailsVisible,
      rating
    }
  },
}
</script>

<style lang="scss" scoped>
@import '@/plugins/vuetify/default-preset/preset/mixins.scss';

.avatar-center {
  top: -2rem;
  left: 1rem;
  border: 3px solid white;
  position: absolute;
}

// membership pricing
@include theme--child(memberpricing-bg) using ($material) {
  background-color: rgba(map-deep-get($material, 'primary-shade'), map-deep-get($material, 'states', 'hover'));
}

.memberpricing-bg {
  position: relative;
}
.membership-pricing {
  text-align: center;
  sup {
    font-size: 3.75rem;
    top: 9px;
  }
}
</style>
