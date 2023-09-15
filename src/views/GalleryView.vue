<script setup></script>
<template>
  <!-- banner -->
  <div class="banner mb-lg-48 mb-32">
    <h2 class="text-center py-96 text-white">價目表</h2>
  </div>
  <!-- main section -->
  <div class="container">
    <div class="row">
      <!-- 類別 filter -->
      <div class="col-12 col-lg-5 d-flex mb-32">
        <div class="border-bottom border-3 border-primary m-16 fs-20">類別</div>
        <ul class="d-flex align-items-center">
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">沾粉美甲</a></li>
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">凝膠美甲</a></li>
        </ul>
      </div>

      <!-- end 類別 filter -->
      <!-- 風格 filter -->
      <div class="col-12 col-lg-7 d-flex mb-32">
        <div class="border-bottom border-3 border-primary m-16 fs-20">風格</div>
        <ul class="d-flex align-items-center">
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">夏天</a></li>
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">冬天</a></li>
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">單色</a></li>
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">水鑽</a></li>
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">漸層</a></li>
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">貓眼</a></li>
          <li class=""><a href="#" class="text-black fs-16 py-16 px-8">法式</a></li>
        </ul>
      </div>
      <!-- end 風格 filter -->
    </div>
    <!-- start gallery -->
    <div class="container">
      <div class="row">
        <div class="col-4 col-lg-3 mb-24">
          <div class="gallery"></div>
        </div>
        <div class="col-4 col-lg-3 mb-24">
          <div class="gallery"></div>
        </div>
        <div class="col-4 col-lg-3 mb-24">
          <div class="gallery"></div>
        </div>
        <div class="col-4 col-lg-3 mb-24">
          <div class="gallery"></div>
        </div>
        <div class="col-4 col-lg-3 mb-24">
          <div class="gallery"></div>
        </div>
        <div class="col-4 col-lg-3 mb-24">
          <div class="gallery"></div>
        </div>
        <div class="col-4 col-lg-3 mb-24">
          <div class="gallery"></div>
        </div>
        <div class="col-4 col-lg-3">
          <div class="gallery"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
a:hover {
  color: #bb9cd8 !important;
}

.gallery {
  background: #bb9cd8;
  height: 300px;
}
</style>
