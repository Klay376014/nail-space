<script setup>
</script>
<template>
  <div class="banner mb-lg-48 mb-32">
    <h2 class="text-center py-96 text-white">註冊</h2>
  </div>
     <div class="container mb-60 flex-grow-1">

      <div class="col-lg-4 col-md-6 col-12 mx-auto text-center mt-md-60 mt-24">
        
        <h3 class="fw-bold fs-24 my-16 text-primary">會員註冊</h3>
        <form class="needs-validation text-start" method="POST">

          <div class="mb-16">
            <label class="noto-tc-sans form-label mb-0" for="user_login">帳號</label>
            <input class="mt-8 w-100 form-control form-control-lg border border-2 border-primary login-input"
              type="text" id="user_login" placeholder="請輸入帳號" aria-label="請輸入帳號" required>
            <div class="invalid-feedback">
              請輸入帳號
            </div>
          </div>

          <div class="mb-lg-32 mb-24">
            <label class="noto-tc-sans form-label mb-0" for="user_password">密碼</label>
            <input class="mt-8 w-100 form-control form-control-lg border border-2 border-primary login-input"
              type="password" id="user_password" placeholder="請輸入密碼" aria-label="請輸入密碼" required>
            <div class="invalid-feedback">
              請輸入密碼
            </div>
          </div>

          <button type="submit " class="btn btn-submit btn-secondary w-100 py-8 mt-20">
            <span class="me-4 fs-20 fw-bold noto-tc-sans">註冊</span>
            <i class="icofont-rounded-double-right"></i>
          </button>

        </form>
      </div>

    </div>


</template>
<style scoped lang="scss">
h3 {
    letter-spacing: 1.2px;
}

.login-icon {
    height: 32px;
    width: 32px;
}

.login-input {
    background-color: #efdff7;
    &::placeholder {
        color: #878787 !important;
        font-size: 20px !important;
    }
}


.btn-submit:hover {
    color:#efdff7!important;
    background-color: #1F0F39!important;  
  }
</style>  