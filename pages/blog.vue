<template>
  <div class="blog">
    <h3>List Blog</h3>
    <table class="table table-bordered">
  <thead>
    <tr>
      <th scope="col">Id</th>
      <th scope="col">Tin</th>
      <th scope="col">Loại</th>
      <th scope="col">Trạng Thái</th>
      <th scope="col">Vị trí</th>
      <th scope="col">Ngày public</th>
      <th scope="col">Edit</th>
      <th scope="col">Delete</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
    <tr>
      <th scope="row">2</th>
 <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
    <tr>
    <th scope="row">1</th>
 <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
    <tr>
      <th scope="row">2</th>
        <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
    <tr>
    <th scope="row">1</th>
    <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
    <tr>
      <th scope="row">2</th>
     <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
    <tr>
    <th scope="row">1</th>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
    <tr>
      <th scope="row">2</th>
       <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
  </tbody>
</table>
  </div>
</template>

<script>
import Header from "./header.vue"

export default {
  components : {

  }
}
</script>

<style>
.blog {
 width: 70%;
 height: 80vh;
 float: left;
}
td{
  border: 2px solid black;
}
</style>
