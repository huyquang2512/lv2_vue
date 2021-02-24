<template>
  <div class="blog">
    <h3>Search Blog</h3><br>
    <div>Tiêu đề &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input style="width: 80%;"></div><br>
<button type="button" class="btn btn-success">Search</button><br>
<br>
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
      <td>5</td>
      <td>6</td>
    </tr>
    <tr>
      <th scope="row">2</th>
         <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <th scope="row">1</th>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>5</td>
      <td>6</td>
    </tr>
    <tr>
      <th scope="row">2</th>
         <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <th scope="row">1</th>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>5</td>
      <td>6</td>
    </tr>
    <tr>
      <th scope="row">2</th>
         <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <th scope="row">1</th>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>5</td>
      <td>6</td>
    </tr>
    <tr>
      <th scope="row">2</th>
         <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
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
.table-bordered{

}


</style>
