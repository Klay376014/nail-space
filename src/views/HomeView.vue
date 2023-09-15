<script setup>
import Card from "../components/CardItem.vue";

const products = ["product-1", "product-2", "product-3"];
</script>
<template>
  <div class="banner mb-lg-48">
    <div class="container pt-60 pt-lg-120 pb-32 pb-lg-60 d-flex flex-column">
      <h2 class="text-white fs-48 fs-lg-64 mb-lg-20 text-center text-lg-start">Yvonne's Nail Space</h2>
      <p class="text-white text-center fs-20 fs-lg-32">我的美甲空間　你的美好時間</p>
      <button type="button" class="btn btn-secondary mx-auto ms-lg-auto me-lg-0 py-12 px-20 fs-lg-20">立即線上預約</button>
    </div>
  </div>

  <div class="owner container mt-40 mt-lg-80 mb-40 mb-lg-80">
    <div class="row gx-60">
      <div class="col-lg-4">
<<<<<<< HEAD
        <img src="https://scontent.ftpe7-3.fna.fbcdn.net/v/t1.6435-9/173481069_10208689672555239_4432502272894464060_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=c_5WjnwYYygAX-wgmlI&_nc_ht=scontent.ftpe7-3.fna&oh=00_AfDFoVZJDSJ_YkrcaCoQ07iVJPigUg411sAvn32CQVVHlw&oe=652BF98C" alt="owner" class="img-fluid">
      </div>
      <div class="col-lg-8 d-flex flex-column justify-content-between">
        <div>
          <h2 class="mb-40 fs-lg-48">旅澳歸台美甲師 Yvonne</h2>
          <p class="mb-20 fs-lg-20">Yvonne 在澳洲學習到了新的美甲產品與新技術-沾粉指甲 (Dip powder) ，親眼見證了許多客人的心路歷程！</p>
          <p class="fs-lg-20">眾多客戶分享的故事中，讓 Yvonne 深深體會到，美甲不只是奢侈品，不只是追求流行的標誌，美甲可以是日常，更可以是改變你的心情、進而提升信心的工具。</p>
        </div>
        <button type="button" class="btn btn-outline-primary ms-auto fs-lg-20">更多關於 Yvonne </button>
=======
        <img src="https://images.unsplash.com/photo-1553072272-33ad001b2df0?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1935&q=80" alt="owner" class="img-fluid">
      </div>
      <div class="col-lg-8 d-flex flex-column justify-content-between">
        <div>
          <h2 class="mb-40 fs-lg-48">旅澳歸台美甲師Yvonne</h2>
          <p class="mb-20 fs-lg-20">Yvonne在澳洲學習到了新的美甲產品與新技術-沾粉指甲(Dip powder)，親眼見證了許多客人的心路歷程！</p>
          <p class="fs-lg-20">眾多客戶分享的故事中，讓Yvonne深深體會到，美甲不只是奢侈品，不只是追求流行的標誌，美甲可以是日常，更可以是改變你的心情、進而提升信心的工具。</p>
        </div>
        <button type="button" class="btn btn-outline-primary ms-auto fs-lg-20">更多關於Yvonne</button>
>>>>>>> 665d8157481b155e4b904776ee79d1ceb320422f
      </div>
    </div>
  </div>

  <div class="container">
    <div class="bg-primary py-16 text-center fs-24 text-white mb-40 mb-lg-60">服務項目</div>
    <div class="row gx-60">
      <div class="col-lg-4" v-for="(product, index) in products">
        <Card :image="product" :index="index" :service=true ></Card>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="bg-primary py-16 text-center fs-24 text-white mb-40 mb-lg-60">最新活動</div>
    <div class="row gx-60">
      <div class="col-lg-4" v-for="(product, index) in products">
        <Card :image="product" :index="index" :service=false ></Card>
      </div>
    </div>
  </div>

  <div class="container pb-40 pb-lg-80">
    <div class="bg-primary py-16 text-center fs-24 text-white mb-40 mb-lg-60">熱門美甲</div>
    <div class="row gx-60">
      <div class="col-lg-4 mb-20 mb-lg-0">
        <img src="https://images.unsplash.com/photo-1567169556820-a566b9f53776?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2012&q=80" alt="nail-1">
      </div>
      <div class="col-lg-4 mb-20 mb-lg-0">
        <img src="https://images.unsplash.com/photo-1567169556820-a566b9f53776?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2012&q=80" alt="nail-1">
      </div>
      <div class="col-lg-4 mb-20 mb-lg-0">
        <img src="https://images.unsplash.com/photo-1567169556820-a566b9f53776?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2012&q=80" alt="nail-1">
      </div>
    </div>
  </div>
</template>
