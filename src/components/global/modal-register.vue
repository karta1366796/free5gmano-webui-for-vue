<template>
  <div class="modal fade" id="register_Modal" ref="modal_register" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">註冊</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <div class="row">
            <div class="col-12 mb-3">
              <label for="account" class="form-label">帳號 :</label>
              <input type="text" class="form-control input-custom" id="account" placeholder="帳號">
            </div>
            <div class="col-12 mb-3">
              <label for="email" class="form-label">信箱 :</label>
              <input type="email" class="form-control input-custom" id="email" placeholder="信箱">
            </div>
            <div class="col-12 col-md-6 mb-3">
              <label for="password" class="form-label">密碼 :</label>
              <input type="password" class="form-control input-custom" id="password" placeholder="密碼">
            </div>
            <div class="col-12 col-md-6 mb-3">
              <label for="password_confirm" class="form-label">再次輸入密碼 :</label>
              <input type="password" class="form-control input-custom" id="password_confirm" placeholder="再次輸入密碼">
            </div>

            <div class="text-center my-2">
              <button @click="ax" class="btn btn-success px-5" data-bs-toggle="modal" data-bs-target="#register_Modal">註 冊</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
// import axios from 'axios';
// const ax = () => {
//   axios.post('http://10.20.1.40:80/basic/register/',{
//     name: "user2",
//     password: "user2",
//     email: "user2@gmail.com"
//   }).then(res=>{
//     console.log(res)
//   })
// }

</script>
<style scoped>
.btn-success {
  background-color: #42b72a !important;
}
.input-custom {
  background-color: #f5f6f7;
}
</style>