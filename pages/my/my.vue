<template>
  <view>
    <button open-type="getUserInfo" @getuserinfo="getUserInfo">denglu</button>
  </view>
</template>

<script>
  export default {
    data() {
      return {
        
      };
    },
    methods:{
      getUserInfo(e){
        console.log(e)
      }
    }
  }
</script>

<style lang="scss">

</style>
