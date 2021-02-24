<template>
  <div class="content">
    <menu-index/>
    <blog-index/>
  </div>
</template>

<script>
import Menu from "./menu.vue"
import Blog from "./blog.vue"
export default {
    components : {
    "menu-index": Menu,
    "blog-index": Blog,
    }
}
</script>

<style>
.content{
  width: 100%;
  height: auto;
  margin-top: 100px;
}
</style>
