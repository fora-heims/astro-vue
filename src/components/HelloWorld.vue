<template>
  <div class="hello">
    <Header name="astro-vue" />
    <h1>{{ msg }}</h1>
    <Main thing="0" />
    <Footer nam="basries" />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Main from "./Main.vue";
import Footer from "./Footer.vue";

export default {
  name: "HelloWorld",
  components: {
    Header,
    Main,
    Footer,
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
