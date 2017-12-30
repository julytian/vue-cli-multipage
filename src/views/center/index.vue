<template>
<div class="home">
  <div class="title v_center p100">
      <h1 class="flex">center</h1>
  </div>
</div>
</template>

<script>
export default {
  mounted () {
    console.log('center.name')
  }
}
</script>

<style lang="scss" scoped>
  .title{
    .flex{
      display:flex;
    }
  }
</style>