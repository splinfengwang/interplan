<template>
  <div class="home">
    <h1>LOVE</h1>
    <h1 type="blue">LOVE</h1>
    <Button>Default</Button>
    <Button type="primary">Primary</Button>
    <Button type="ghost">Ghost</Button>
    <Button type="dashed">Dashed</Button>
    <Button type="text">Text</Button>
    <br><br>
    <Button type="info">信息按钮</Button>
    <Button type="success">成功按钮</Button>
    <Button type="warning">警告按钮</Button>
    <Button type="error">错误按钮</Button>
  </div>
</template>

<script>
export default {
  
}
</script>
<style lang="scss" scoped>
  .home {
    h1{
      color: red;
      &[type="blue"]{
        color: blue;
      }
    }
  }
</style>

