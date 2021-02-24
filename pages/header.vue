<template>
  <div class="header">
    <div class="logo">
      <img src="https://cdn1.vieclam24h.vn/upload/files_cua_nguoi_dung/logo/2018/09/10/1536546919_logo-01.jpg" alt="" style="width: 30%;">
    </div>
    <div class="name"> <h1>Blog Management</h1></div>
    <content-index>
    </content-index>
  </div>
</template>

<script>
import Menu from "./menu.vue"
import Blog from "./blog.vue"
import Content from "./content.vue"
export default {
    components : {
    "menu-index": Menu,
    "blog-index": Blog,
    "content-index": Content,
    }
}
</script>

<style>
.header{
  width: 100%;
  height:70px;
  margin: 0px;
}
.logo{
  width: 30%;
  height:70px;
  margin: 0px;
  float: left;
}
.name{
  width: 40%;
  float: left;
  height:70px;
  margin: 0px;
}
</style>
