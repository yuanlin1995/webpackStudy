<!--渲染模版-->
<template>
  <h1>{{ msg }}</h1>
</template>

<!--样式描述-->
<style>
h1 {
  color: #f00;
}
</style>

<!--组件逻辑-->
<script>
export default {
  data () {
    return {
      msg: 'Hello,Webpack'
    }
  }
}
</script>
