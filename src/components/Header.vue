<script setup>
</script>
<template>
  <header class="bg-secondary">
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-primary bg-secondary">
        <div class="container-fluid">
          <h1 class="navbar-brand"><a href="/">Yvonne's Nail Space</a></h1>
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
              class="navbar-nav me-auto mb-2 mb-lg-0 flex-row flex-wrap flex-lg-nowrap w-100 text-center align-items-center fw-bold"
            >
              <li class="nav-item w-50 d-none d-lg-block bd-bottom">
                <RouterLink class="nav-link px-0 text-white active" to="/">首頁</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 text-white" to="/about">品牌故事</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 text-white" to="/">服務項目</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 text-white" to="/">價目表</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 text-white" to="/">作品集</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 text-white" to="/">文章介紹</RouterLink>
              </li>
              <li class="nav-item w-50 bd-bottom">
                <RouterLink class="nav-link px-0 text-white" to="/">Q&A</RouterLink>
              </li>
              <li class="nav-item d-lg-none w-100">
                <RouterLink class="nav-link" to="/"
                  ><button class="btn btn-primary px-5">登入／註冊</button></RouterLink
                >
              </li>
              <li class="nav-item d-none d-lg-flex text-lg-end w-75">
                <button class="btn btn-primary flex-grow-1 px-2">
                  <RouterLink class="nav-link text-white" to="/">登入／註冊</RouterLink>
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