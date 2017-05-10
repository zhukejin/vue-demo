<template>
  <div class="hello">
    <div class="card">
        许愿卡
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .card {
        margin-top: 10px;
        background-color: #f5317f;
        color: rgb(255,255,255);
        font-weight: normal;

        display: flex;
        justify-content: center;
        align-items: center;

        height: 45px;
    }


</style>
