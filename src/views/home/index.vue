<template>
  <div>
    <van-field v-model="tel" type="tel" label="手机号" />
  </div>

</template>

<script>

  export default {
    data() {
      return {
        active: 2
      }
    }
  }
</script>

<style  scoped>
  .test-viewport {
    width: 500px;
    height: 100px;
    font-size: 40px;
    text-align: center;
    line-height: 100px;
    background: #13b5b1;
  }
  </style>
