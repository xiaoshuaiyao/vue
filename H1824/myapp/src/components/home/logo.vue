<template>
  <div class="logo">
     <div class="logo_top">
         <h2>{{blank}}</h2>
     </div>
     <div class="logo_img">
         <img src="https://www.bestsign.cn/_nuxt/img/e736dae.jpg" alt="">
     </div>
     <div class="butt">
        <a href="">{{use}} <span class="iconfont">&#xe632;
</span></a>
     </div>
  </div>
  
</template>

<script>
export default {
  name: "Logo",
  data() {
    return {
         blank:"50万+创新企业业正在使用",
         use:"它们如何使用"
    };
  }
};
</script>

<style scoped lang="scss">
    .logo{
        width: 355.2px;
        height: 480.9px;
        padding: 50px 10px;
    }
    .logo_top{
        width: 100%;
        height: 77.2px;
        padding-bottom: 50px;
    }
    .logo_top>h2{
        font-size: 24px;
        font-weight: 400;
        text-align: center;
        line-height: 77.2px;
    }
    .logo_img{
        height: 285.487px;
         padding-bottom: 30px;
    }
    
    .logo_img>img{
        width: 355px;
        height: 285.487px;
    }
    .butt{
        width: 100%;
        height: 50px;
        text-align: center;
    }
    .butt>a{
        height: 50px;
        line-height: 50px;
        font-size: 13px;
        color: #008475;
    }
</style>