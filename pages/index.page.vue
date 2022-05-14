<template>
  <h1>Hello! Thanks for your attention :)</h1>
  <p>Please navigate <a href="/random">here</a></p>
  <div class="box">
    <p>.box styles are only loaded when this page is opened in SSR</p>
  </div>
</template>

<style lang="scss" scoped>
.box {
  background: #000;
  color: #fff;
  padding: 100px 20px;
}
</style>
