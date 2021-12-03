<template>
  <div class="header">{{ name }}</div>
</template>
<script>
export default {
  name: "Header",
  props: {
    name: String,
  },
};
</script>
<style>
.header {
  background-color: #8b9eb7dd;
  color: #91f5ad;
  position: fixed;
  top: 0%;
  display: flex;
  width: fill;
  font-family: "Courier New", Courier, monospace;
  font-weight: 700;
  font-size: 24px;
  padding: 5px;
}
</style>
