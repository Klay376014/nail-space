<script setup></script>

<template>
  <!-- banner -->
  <div class="banner mb-lg-48 mb-32">
    <h2 class="text-center py-96 text-white">服務項目</h2>
  </div>
  <!-- main section -->
  <div class="container">
    <div class="row">
      <!-- 1 -->
      <div class="col-lg-6 d-none d-lg-block">
        <img
          src="https://lh3.googleusercontent.com/CpUNKN_2tD8xM8CIU1RRuSgzsJ4VDJ7NNVRh53pbYrGUJqXnYSW_BIjGaWLh91gTnru6l6NQ1VsEvURfR5w6uMYdyKd8Ujlv5gRya1YnPnz3nf4AjnyvVxnblGqXJBDbYMVKEo-h7A=w2400"
          alt=""
        />
      </div>
      <div
        class="col-12 col-lg-6 p-16 d-flex flex-column justify-content-between mb-32 pic-1"
        style="height: 500px"
      >
        <div>
          <h3 class="">沾粉指甲</h3>
          <p class="">123456</p>
        </div>
        <button type="button" class="btn btn-lg btn-outline-primary align-self-end">MORE</button>
      </div>
      <!-- 1 -->
      <!-- 2 -->
      <div
        class="col-12 col-lg-6 p-16 d-flex flex-column justify-content-between mb-32 pic-1"
        style="height: 500px"
      >
        <div>
          <h3 class="">凝膠指甲</h3>
          <p class="">123456</p>
        </div>
        <button type="button" class="btn btn-lg btn-outline-primary align-self-end">MORE</button>
      </div>
      <div class="col-lg-6 d-none d-lg-block">
        <img
          src="https://lh3.googleusercontent.com/CpUNKN_2tD8xM8CIU1RRuSgzsJ4VDJ7NNVRh53pbYrGUJqXnYSW_BIjGaWLh91gTnru6l6NQ1VsEvURfR5w6uMYdyKd8Ujlv5gRya1YnPnz3nf4AjnyvVxnblGqXJBDbYMVKEo-h7A=w2400"
          alt=""
        />
      </div>
      <!-- 2 -->
      <!-- 3 -->
      <div class="col-lg-6 d-none d-lg-block">
        <img
          src="https://lh3.googleusercontent.com/CpUNKN_2tD8xM8CIU1RRuSgzsJ4VDJ7NNVRh53pbYrGUJqXnYSW_BIjGaWLh91gTnru6l6NQ1VsEvURfR5w6uMYdyKd8Ujlv5gRya1YnPnz3nf4AjnyvVxnblGqXJBDbYMVKEo-h7A=w2400"
          alt=""
        />
      </div>
      <div
        class="col-12 col-lg-6 p-16 d-flex flex-column justify-content-between mb-32 pic-1"
        style="height: 500px"
      >
        <div>
          <h3 class="">沾粉指甲</h3>
          <p class="">123456</p>
        </div>
        <button type="button" class="btn btn-lg btn-outline-primary align-self-end">MORE</button>
      </div>
      <!-- 3 -->
      <!-- 4 -->
      <div
        class="col-12 col-lg-6 p-16 d-flex flex-column justify-content-between mb-32 pic-1"
        style="height: 500px"
      >
        <div>
          <h3 class="">凝膠指甲</h3>
          <p class="">123456</p>
        </div>
        <button type="button" class="btn btn-lg btn-outline-primary align-self-end">MORE</button>
      </div>
      <div class="col-lg-6 d-none d-lg-block">
        <img
          src="https://lh3.googleusercontent.com/CpUNKN_2tD8xM8CIU1RRuSgzsJ4VDJ7NNVRh53pbYrGUJqXnYSW_BIjGaWLh91gTnru6l6NQ1VsEvURfR5w6uMYdyKd8Ujlv5gRya1YnPnz3nf4AjnyvVxnblGqXJBDbYMVKEo-h7A=w2400"
          alt=""
        />
      </div>
      <!-- 4 -->
    </div>
  </div>
</template>

<style scoped lang="scss">
img {
  background-position: center;
  background-size: cover;
  object-fit: cover;
  height: 500px;
}
.pic-1 {
  background-image: url('https://lh3.googleusercontent.com/CpUNKN_2tD8xM8CIU1RRuSgzsJ4VDJ7NNVRh53pbYrGUJqXnYSW_BIjGaWLh91gTnru6l6NQ1VsEvURfR5w6uMYdyKd8Ujlv5gRya1YnPnz3nf4AjnyvVxnblGqXJBDbYMVKEo-h7A=w2400');
  background-position: center;
  background-size: cover;
  object-fit: cover;
  position: relative;
  z-index: -1;
  &:after {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    backdrop-filter: blur(10px);
    z-index: -1;
  }
  @media (min-width: 992px) {
    background-image: url('') !important;
  }
}
.col-12 {
  @media (min-width: 992px) {
    background-color: #ffffff !important;
  }
}
</style>
