<template>
  <div class="menu">
    <ul>
  <li><nuxt-link to="/blog"><button>List</button></nuxt-link></li>
  <li><nuxt-link to="/blogNew"><button>New</button></nuxt-link></li>
  <li><nuxt-link to="/blogSearch"><button>Search</button></nuxt-link></li>
  <li><nuxt-link to="/blogEdit"><button>Edit</button></nuxt-link></li>
</ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.menu{
  width: 30%;
  float: left;
  height: 300px;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

li button {
  font-weight: bold;
  border: 1px solid black;
  font-size: 20px;
  text-align: center;
  display: block;
  width: 90%;
  height: 70px;
  background-color:white;
}
button:link{
  background-color: #dddddd;
}
</style>
