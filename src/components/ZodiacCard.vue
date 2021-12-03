<template>
  <div>
    <img src="" alt="" />
    <span>{{ name }}</span>
    <span>{{ dates }}</span>
  </div>
</template>
<script>
export default {
  name: "ZodiacCard",
  props: {
    name: String,
    dates: String,
  },
};
</script>
<style></style>
