<script setup>
import Card from "../components/card-item.vue";

const products = ["product-1", "product-2", "product-3", "product-4"];
</script>
<template>
  <div class="container-lg">
    <h2 class="lh-base">熱門產品</h2>
    <div class="row">
      <div class="col-lg-6" v-for="(product, index) in products">
        <Card :image="product" :index="index+1"></Card>
      </div>
    </div>
  </div>
</template>
<style></style>