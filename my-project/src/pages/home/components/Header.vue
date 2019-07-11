<template>
  <div class="header">
   <div class="header-left">返回</div>
    <div class="header-input">输入城市景点游玩主题</div>
    <div class="header-right">城市</div>
  </div>
</template>
<script>
  export default{
    name:'HomeHeader'
  }
</script>
<style lang="stylus" scoped>
.header{
  display:flex;
  line-height:.86rem;
  background:#00bcd4;
  color:#fff

}
  .header-left{
    width:.64rem;
    float:left
  }

   .header-input{
     flex:1
     background:#fff;
     border-radius: .1rem;
     margin-top: .12rem;
     height:.64rem;
     margin-left: .12rem;
     color:#ccc;
   }

    .header-right{
      float:right;
      width:1.24rem;
      text-align: center;
    }

</style>
