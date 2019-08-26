<template>
  <div class=".wrapper">
  <swiper :options="swiperOption" >
    <!-- slides -->
    <swiper-slide v-for="item of swiperList" :key="item.id">
      <img class="swiper-img" :src="item.imgUrl" >
    </swiper-slide>

    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>

  </swiper>
  </div>
</template>

<script>
export default{
  name:'HomeSwiper',
  data (){
    return{
      swiperOption:{
        pagination:'.swiper-pagination'
      },
      swiperList:[{
        id:'000',
        imgUrl:"https://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20196/ebf7306335a5e060dbbfe42b8e8ede9f.jpg_945x288_da043916.jpg"
      },{
        id:'001',
        imgUrl:"//mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20197/a685001bbf5e77a203ff8815e953efbe.jpg_945x288_52b6ec01.jpg"
      },{
      id:'002',
        imgUrl:"https://h-des-activity-fecp.qunarzz.com/h_des_activity_fe_h_des_activity_fe/973dc1ae0da73a58410186df08ff25cb.jpg"
    }]
    }

  }
}

</script>
<style lang="stylus" scoped>
  .wrapper{
    width:100%;
    height:0;
    overflow: hidden;;
    padding-bottom: 31.25%;
  }
  .swiper-img{
    width:100%
  }
</style>
