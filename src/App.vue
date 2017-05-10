<template>
  <div id="app">
    <div class="title">
      目前拥有 {{ number }} 张卡片
    </div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      number: 1
    }
  }
}
</script>
<style>
  * {
    box-sizing: border-box;
  }

  html, body {
    padding: 0;
    margin: 0;
  }

  .title {
    background-color: #fcb8d3;
    color: rgba(0,0,0,.65);
    font-weight: normal;

    display: flex;
    justify-content: center;
    align-items: center;

    height: 45px;
  }
</style>
