<template>
  <div class="container">
   <header-index></header-index>
  </div>
</template>

<script>
import Header from "./header.vue"

export default {
  components : {
    "header-index": Header,

  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  /* background-color: red; */
}


</style>
