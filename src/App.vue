<template>
  <div id="app">
    <p class="p">我是颜色</p>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scope lang="less">
  #app{
    .p{
      color: orange;
    }
  }
</style>
