<template>
<div class="icons">
  <swiper  >
    <swiper-slide>
 <div class="icon">
   <div class="icon-img">
     <img class="icon-img-content" src="http://s.qunarzz.com/homenode/images/touchheader/hotel.png"/>
   </div>

   <p class="icon-desc">酒店</p>
 </div>
    </swiper-slide>
  </swiper>
</div>


</template>

<script>
export default{
  name:'HomeIcons'
}

</script>

<style lang="stylus" scoped>
.icons {
  height:0;
  padding-bottom:50%;
  overflow:hidden;

  width:100%
}
.icon{
  position: relative;
  width:25%;
  float:left;
  padding-bottom: 25%;

  overflow: hidden;
  height:0;
}
  .icon-img{
    position: absolute;
    top:0;
    left:0;
    right:0;
    bottom:.44rem;

    box-sizing: border-box;
    padding: .1rem;
  }
  .icon-img-content{
    height:100%;
    display: block;
    margin: 0 auto;

  }
  .icon-desc{
    position: absolute;
    height:.44rem;
   line-height: .44rem;
    left:0;
    right:0;
    bottom:0;
    color:#333;
    text-align: center;
  }
</style>
