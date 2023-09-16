<script setup></script>
<template>
  <!-- banner -->
  <div class="banner mb-lg-48 mb-32">
    <h2 class="text-center py-96 text-white">作品集</h2>
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
    <div class="container mb-40">
      <div class="row">
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class=" " src="/images/gallery-1.jpg"
          alt=""/>
          </div>
        </div>
           <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class=" " src="/images/gallery-2.jpg"
          alt=""/>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class=" " src="/images/gallery-3.jpg"
          alt=""/>
          </div>
        </div>    
       <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-4.jpg"
          alt=""/>
          </div>
        </div>    
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-5.jpg"
          alt=""/>
          </div>
        </div>    
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-6.jpg"
          alt=""/>
          </div>
        </div>    
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-7.png"
          alt=""/>
          </div>
        </div>    
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-8.jpg"
          alt=""/>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-9.jpg"
          alt=""/>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-10.jpg"
          alt=""/>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-11.jpg"
          alt=""/>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-3 mb-24">
          <div class="gallery rounded">
          <img class="" src="/images/gallery-12.jpg"
          alt=""/>
          </div>
        </div>
      </div>
    </div>
   <div class="pagination mb-40">
        <nav aria-label="page-navigation" class="w-100 h-auto">
          <ul class="pagination justify-content-center mb-0">
            <li class="page-item lh-1"><a class="page-link link-primary p-1 border-primary" href="#"><span class="material-icons">chevron_left</span></a></li>
            <li class="page-item ms-8"><a class="page-link link-primary pb-1 border-primary" href="#">1</a></li>
            <li class="page-item ms-8"><a class="page-link link-primary pb-1 border-primary" href="#">2</a></li>
            <li class="page-item ms-8"><a class="page-link link-primary pb-1 border-primary" href="#">3</a></li>
            <li class="page-item lh-1 ms-8"><a class="page-link link-primary p-1 border-primary" href="#"><span class="material-icons">chevron_right</span></a></li>
          </ul>
        </nav>
      </div>
    </div>
</template>


<style scoped lang="scss">
.gallery {
  border:8px solid #bb9cd8;
}
.page-link {
  &:hover
  {
    background-color: #bb9cd8 !important;
    color:#fff !important;
  }
}
</style>
