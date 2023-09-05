
<template>
  <div id="app">
    <homeTable />
  </div>
</template>

<script>
import homeTable from '@/components/HomeTable.vue'

export default {
  name: 'App',
  components: {
    homeTable
  }
}
</script>

<style lang="less" scoped>
#app{
  width: 100%;
  height: 100vh;
}
</style>
