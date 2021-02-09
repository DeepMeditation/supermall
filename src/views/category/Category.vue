<template>
  <div class="wrapper" ref="scroll">
    <ul class="content">
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
      <li>数据1</li>
    </ul>
  </div>
</template>

<script>
import BScroll from 'better-scroll'

export default {
  name: "Category",
  data() {
    return {
      scroll: null
    }
  },
  mounted() {
    this.scroll = new BScroll(this.$refs.scroll, {
      // probeType: 3,
      // pullUpLoad: true
    })
  }
}
</script>

<style scoped>
.wrapper {
  height: 150px;
  background-color: greenyellow;

  overflow: hidden;
}
</style>
