<script setup>
const props = defineProps({ image: String, index: Number, service: Boolean })

const services = [
  {
    title: '沾粉指甲',
    content:
      '沾粉指甲技術可為指甲提供強大的保護，共使指甲看起來更美觀。由於其耐用性，這種技術特別適合那些容易將指甲磨損或斷裂的人。'
  },
  {
    title: '手足保養',
    content:
      '手指關節部分是角質容易堆積的地方，一旦角質堆積過多，關節部位看起來就會較為暗沉。可以約莫每兩週一次為手部進行去角質。'
  },
  {
    title: '熱蠟除毛',
    content:
      '它是利用熱蠟將毛髮從毛囊中拔除的過程。這種方法可以在身體的不同部位使用，共且是一種相對持久的去毛方式，通常可以維持數週至數月的效果。'
  }
]

const events = [
  {
    title: '初夏特價活動款',
    content: "畢業季優惠-憑學生證活動款可以再折$50，夏天就是要清清爽爽，趁著端午連假前美一波~快點來看看吧！",
    date: '2023 / 7 / 20'
  },
  {
    title: '母親節禮物',
    content: "母親節到了，你是不是在煩惱要送給媽媽什麼禮物？是不是在想著怎樣讓媽媽感受到你的心意？不要再猶豫了，我們的美甲服務為你解決煩惱！",
    date: '2023 / 5 / 1'
  },
  {
    title: '花季特輯',
    content: "春日花季，讓你的指尖綻放出美麗花朵的色彩！四月設計款為你打造一場美甲盛宴，感受到春天的氣息並享受美麗的花卉美甲！",
    date: '2023 / 4 / 2'
  }
]
</script>
<template>
  <div class="card mb-40">
    <img :src="'images/' + props.image + '.jpg'" class="card-img-top" alt="product" />
    <div class="card-body px-16">
      <h4 class="card-title text-center mb-24" v-if="props.service">{{ services[props.index].title }}</h4>
      <h4 class="card-title text-center mb-24" v-else>{{ events[props.index].title }}</h4>
      <p class="card-text mb-24" v-if="props.service">
        {{ services[props.index].content }}
      </p>
      <p class="card-text mb-24" v-else>
        {{ events[props.index].content }}
      </p>
      <a href="#" class="btn btn-primary mx-auto d-block w-50 py-8" v-if="props.service"
        >立即預約</a
      >
      <p class="text-end" v-else>{{ events[props.index].date }}</p>
    </div>
  </div>
</template>
<style></style>