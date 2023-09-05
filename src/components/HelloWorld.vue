<template>
<div>
<div id="luckysheet" class="sheet"></div>

</div>
</template>

<script>
export default {
  name: 'luckySheet',
  mounted () {
    this.init()
  },
  methods: {
    init () {
      const options = {
        container: 'luckysheet', // luckysheet为容器id
        title: 'luckysheet', // 表 头名
        lang: 'zh' // 中文
      }
      window.luckysheet.create(options)
    }
  }
}
</script>

<style lang="less" scoped>
.sheet{
  width:100%;
  height: 800px;
}
</style>
