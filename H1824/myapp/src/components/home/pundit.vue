<template>
  <div class="pundit">
     <div class="pundit_top">
         <h2>{{index}}</h2>
     </div>
     <div class="pundit_img">
         <ul>
             <li v-for="item in pundits">
               <div class="pundit_img_top">
                   <img :src="item.img" alt="">
               </div>
               <div class="pundit_img_middle">
                   <p>{{item.list}}</p>
               </div>
               <div class="pundit_img_bottom">
                   <span>{{item.iso}}</span>
               </div>
             </li>
         </ul>
         <ul>
             <li v-for="item in padds">
               <div class="pundit_img_tops">
                   <img :src="item.img" alt="">
               </div>
               <div class="pundit_img_middle">
                   <p>{{item.list}}</p>
               </div>
               <div class="pundit_img_bottom">
                   <span>{{item.iso}}</span>
               </div>
             </li>
         </ul>
     </div>
  </div>
  
</template>

<script>
export default {
  name: "Pundit",
  data() {
    return {
         index:"国内权威安全认证",
         pundits:[
             {
                 img:"https://www.bestsign.cn/_nuxt/img/19af1f1.jpg",
                 list:"全球认可的国际安全标准",
                 iso:"ISO/IEC27001信息安全管理认证"
             },
             {
                 img:"https://www.bestsign.cn/_nuxt/img/99ac735.jpg",
                 list:"保护用户个人隐私数据安全",
                 iso:"ISO/IEC27018信息安全管理认证"
             },           
         ],
         padds:[
             {
                 img:"https://www.bestsign.cn/_nuxt/img/acaeed5.jpg",
                 list:"与支付宝同级别的安全保护",
                 iso:"信息系统安全等级保护三级认证"
             },
             {
                 img:"https://www.bestsign.cn/_nuxt/img/4c5950f.jpg",
                 list:"国家级SaaS服务安全认证",
                 iso:"可信云服务(TRUCS)认证"
             }
         ]
         
    };
  }
};
</script>

<style scoped lang="scss">
   .pundit{
       width: 100%;
       height: 310.93px;
       padding: 50px 0;
       text-align: center;
   }
   .pundit_top>h2{
      width: 100%;
      height: 27.2px;
      padding-bottom: 50px;
      font-size: 24px;
      font-weight: 400;
   }
   .pundit_img{
       width: 100%;
       height: 233.7px;
      
   }
   .pundit_img>ul>li{
       width: 187.6px;
       height: 111.287px;
      
       float: left;
   }
   .pundit_img_top{
       width: 100%;
       text-align: center;
   }
   .pundit_img_top>img{
      display: inline-block;
       width: 80px;
       height: 37.228px;
   }
   .pundit_img_tops>img{
     display: inline-block;
       width: 50px;
       height: 48.228px;
   }
   .pundit_img_middle{
      width: 100%;
   }
   .pundit_img_middle>p{
       margin: 20px auto 10px;
       font-size: 14px;    
   }
   .pundit_img_bottom{
       width: 100%;
   }
</style>