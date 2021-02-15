<template>
  <div>
    <q-page class="flex flex-center">
      <q-carousel
        v-model="slide"
        vertical
        transition-prev="slide-down"
        transition-next="slide-up"
        swipeable
        animated
        control-color="white"
        navigation-icon="radio_button_unchecked"
        navigation
        padding
        arrows
        height="100vh"
        fullscreen
        class="bg-indigo-10 text-white shadow-1 rounded-borders"
      >
        <q-carousel-slide name="style" class="column flex-center" img-src="~assets/bg-1.jpg">
          <div class="q-mt-md text-center">
            <h1 class="title">Dear Jess</h1>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="tv" class="column no-wrap flex-center" img-src="~assets/bg-2.jpg">
          <q-img class="image q-mb-sm" src="~assets/love.svg" width="100px"></q-img>
          <div class="page">
            <span class="title">
              In the beginning, I already knew that we would cross the threshold from friendship into something so much more. Ever since the day that we have communicated with each other, I can already feel a sense of belonging with you. You accepted me for who I am--my authentic and imperfect self. You are the one I am looking for all this time, a person who can love my very being. I know there is a terrible distance between us. But that will not hinder me in exerting all of my love to you. You are the only one that I keep in my heart. The only one that I love so dearly and no one else.
            </span>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="layers" class="column no-wrap flex-center" img-src="~assets/bg-3.jpg">
          <q-img class="image q-mb-sm" src="~assets/couple.svg" width="100px"></q-img>
          <div class="page">
            <span class="title">
              Every morning, the imagery of yours is the first thing that I can perceive with my eyes. The feeling of closeness and the warmth of your morning greetings made me believe that being close to you was never about proximity. It is always about you, thinking about you every moment of my life.
            </span>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="map" class="column no-wrap flex-center" img-src="~assets/bg-4.jpg">
          <q-img class="image q-mb-sm" src="~assets/dad.svg" width="100px"></q-img>
          <div class="page">
            <span class="title">
              I have loved you not because of your physical appearance, not because of what I've heard about you. I have loved you because of your heart, your mind, and your flaws. I have experienced all of it, and I can attest that it is genuine. Your sincerity and kindness that you have shown to me is the best thing that ever happened to me. You are the only person who makes me feel like I'm loved and care for. Your thoughtfulness is what makes you a wonderful human being. Your every flaw makes up the perfect you, it may sound contradicting but I see your imperfections as perfect as you are, a person that I have yearned for all this time.
              </span>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="map-1" class="column no-wrap flex-center" img-src="~assets/bg-5.jpg">
          <q-img class="image q-mb-sm" src="~assets/giftbox.svg" width="100px"></q-img>
          <div class="page">
            <span class="title">
              I am grateful that my love has been reciprocated and acknowledged. I appreciate it a lot. I will always treasure the trust that you have given to me. I will stay in love with you for the longest time possible and always choose you no matter what happens.
              <br />
              <br />
              I love you and happy first monthsary!
            </span>
          </div>
        </q-carousel-slide>
        <q-carousel-slide name="map-2" class="column no-wrap flex-center"  img-src="~assets/bg-6.jpg">
          <div class="q-mt-md text-center">
            <h1 class="title">Sincerely,</h1>
            <h1 class="title">Jovan</h1>
          </div>
        </q-carousel-slide>
      </q-carousel>
    </q-page>
  </div>
</template>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      slide: 'style',
      lorem: 'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaque voluptatem totam, architecto cupiditate officia rerum, error dignissimos praesentium libero ab nemo.'
    }
  }
}
</script>
<style lang="scss" scoped>
span.title {
  font-family:  Times
}
h1.title {
  font-family: LovinSummer;
  font-size: 2em;
  margin: 0;
  padding: 0;
  line-height: 2em;
}

.page{
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.page .title{
  width: 50vw;
  font-size: 1.9vh;
}

</style>
