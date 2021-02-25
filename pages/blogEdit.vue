<template>
   <div class="blogEdit">
      <h1>Edit Blog</h1>
      <p>Tiêu đều</p>
      <input type="text" style="width: 50%;">
      <p>Mô tả ngắn</p>
      <input type="text" style="width: 50%;">
      <p>Mô tả ngắn</p>
      <textarea name="" id="" cols="30" rows="10" style="width: 50%;"></textarea>
      <p>Hình ảnh </p>
      <input type="file" name="" id=""/>
      <p>Loại</p>
      <select>
      <option value="">Thời Sự</option>
      <option value="">Saab</option>
      <option value="">Opel</option>
      <option value="">Audi</option>
      </select>
      <p>Vị trí</p>
      <input type="checkbox" name="" id=""><label for="vehicle1"> Việt Nam</label><br>
      <input type="checkbox" name="" id=""><label for="vehicle1"> Châu Âu</label><br>
      <input type="checkbox" name="" id=""><label for="vehicle1"> Châu Á</label><br>
      <input type="checkbox" name="" id=""><label for="vehicle1"> Châu Mỹ</label><br>
      <p>Public</p>
      <input type="radio" name="" id=""><label for="vehicle1"> Yes</label><br>
      <input type="radio" name="" id=""><label for="vehicle1"> No</label><br>
      <p>Date Public</p>
      <input type="date" name="" id="">
      <br><br><br>
      <button type="button" class="btn btn-success">Success</button>
      <button type="button" class="btn btn-primary">Primary</button>
  </div>
</template>

<script>

export default {
  components : {

  }
}
</script>

<style>
.blogEdit {
 width: 70%;
 height: auto;
 float: left;
}
.btn-success{
  margin-left: 40%;
}
p, input, select, textarea{
  margin-left: 3%;
}

</style>
