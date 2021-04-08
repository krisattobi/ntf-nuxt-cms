<template>
  <div>
    <vue-slider id="slider-input" v-model="value" />
  </div>
</template>

<script>
import VueSlider from 'vue-slider-component'
import 'vue-slider-component/theme/antd.css'

export default {
  name: "Slider",
  data: () => ({
    value: 50
  })
}
</script>

<style scoped>

</style>