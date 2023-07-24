<script setup>
const props = defineProps({image:String, index: Number})
</script>
<template>
  <div class="card mb-4">
    <img :src="'images/'+props.image+'.jpg'" class="card-img-top" alt="product" />
    <div class="card-body">
      <h5 class="card-title">{{ `美甲服務${props.index}` }}</h5>
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk of the card's
        content.
      </p>
      <a href="#" class="btn btn-primary">點我預訂</a>
    </div>
  </div>
</template>
<style></style>