<template>
  <main id="new-zodiac">
    <!-- <ZodiacCard v-for:"sign in newZodiac" v-bind:key="sign.name" /> -->
    {{ thing }}
  </main>
</template>
<script>
// import { zodiac } from "../assets/zodiac.js";
// import { Vue } from "vue";
// const newZodiac = new Vue({
//   el: "#new-zodiac",
// });
// import ZodiacCard from "./ZodiacCar.vue";
export default {
  name: "Main",
  components: {
    // ZodiacCard,
  },
  props: {
    thing: Number,
  },
};
</script>
<style>
main {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  margin: 65px 40px;
  padding: 40px 10px;
  justify-content: center;
  background: linear-gradient(
    120deg,
    hsla(71, 86%, 49%, 0.5) 0%,
    hsla(137, 83%, 76%, 0.5) 20%,
    hsla(214, 23%, 63%, 0.5) 40%,
    hsla(270, 29%, 45%, 0.5) 60%,
    hsla(320, 40%, 28%, 0.5) 80%
  );
  border-radius: 20px;
}
</style>
