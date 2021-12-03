<template>
  <footer>
    this app was built to practice learning a new framework / library in a
    self-guided way. Also, I am currently learning react.js, and will probably
    continue to practice replicating what I create in react, in vue as well
  </footer>
</template>
<script>
export default {
  name: "Footer",
  props: {},
};
</script>
<style>
footer {
  background-color: #632a50dd;
  color: #c2e812;
  position: fixed;
  display: flex;
  justify-content: flex-end;
  bottom: 0%;
  width: fill;
  font-family: "Courier New", Courier, monospace;
  font-weight: 500;
  font-size: 15px;
  padding: 5px;
}
</style>
