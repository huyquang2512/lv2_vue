<template>
  <div class="blog col-8">
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
    <tr  v-for="blogs in dataBlog" :key="blogs.id">
      <th scope="row">{{blogs.id}}</th>
      <td>{{blogs.title}}</td>
      <td>2</td>
      <td>{{blogs.public}}</td>
      <td></td>
  <td>{{blogs.data_pubblic}}</td>
      <td><a href="">Edit</a></td>
      <td><button type="button" class="btn btn-outline-danger">Delete</button></td>
    </tr>
  </tbody>
</table>
  </div>
</template>

<script>
import axios from 'axios'

export default {
  components : {

  },
  data(){
    return {
      dataBlog : [],
    }
  },
  mounted() {
    this.listData();
  },
  methods:{
    listData(){
      axios({
  method: 'GET',
  url: 'http://localhost:3000/blogs',
  data: null
}).then(res =>{
 this.dataBlog = res.data;
}).catch(err => {
  console.log(err)
})
    }, deleted(){
       axios.delete('http://localhost:3000/blogs')
                .then(response => {
                    this.dataBlog.splice(id, 4)
                });
                console.log(this.dataBlog);
    }
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
