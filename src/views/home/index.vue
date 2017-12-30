<template>
<div class="home">
  <div class="title v_center p100">
      <div class="flex_item">
        <div class="flex flex_h_center"><div>{{ path+("index.name") }}</div></div>
        <fieldset>
          <legend><i class="iconfont icon-birthday"></i>网站</legend>
          <ul>
            <li>
              <div class="flex">
                <a href="center.html">我的</a>
              </div>
            </li>

          </ul>
        </fieldset>
      </div>
  </div>
</div>
</template>

<script>
export default {
  data: () => ({
    path: '当前位置：'
  }),
  mounted () {
    console.log('index.name')
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