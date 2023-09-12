<script setup>
</script>
<template>
  <header class="bg-secondary">
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-primary bg-secondary">
        <div class="container-fluid">
          <h1 class="navbar-brand"><a href="/nail-space/">Yvonne's Nail Space</a></h1>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul
              class="navbar-nav me-auto mb-8 mb-lg-0 flex-row flex-wrap flex-lg-nowrap w-100 text-center align-items-center fw-bold"
            >
              <li class="nav-item w-50 d-none d-lg-block bd-bottom">
                <RouterLink class="nav-link px-0" to="/">首頁</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0" to="/about">品牌故事</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 " to="/service">服務項目</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 " to="/price">價目表</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 " to="/gallery">作品集</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 " to="/">文章介紹</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 " to="/">Q&A</RouterLink>
              </li>
              <li class="nav-item d-lg-none w-50">
                <RouterLink class="nav-link" to="/"
                  ><button class="btn btn-primary px-48">登入</button></RouterLink
                >
              </li>
              <li class="nav-item d-lg-none w-50">
                <RouterLink class="nav-link" to="/"
                  ><button class="btn btn-primary px-48">註冊</button></RouterLink
                >
              </li>
              <li class="nav-item d-none d-lg-flex text-lg-end w-100">
                <button class="btn btn-primary px-8 me-16">
                  <RouterLink class="nav-link" to="/">登入</RouterLink>
                </button>
                <button class="btn btn-primary px-8">
                  <RouterLink class="nav-link" to="/">註冊</RouterLink>
                </button>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>
<style></style>
