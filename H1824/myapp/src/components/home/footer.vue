<template>
  <div class="footer">
     <div v-for="item in fonts" class="footer_font"><p>{{item}}</p></div>
  </div>
  
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
         fonts:["服务等级协议","用户协议","数字证书使用协议","隐私政策","安全白皮书"]
    };
  }
};
</script>

<style scoped lang="scss">
    .footer{
        position: fixed;
        bottom: 0;
        width: 351.2px;
        height: 39.2px;
        padding: 12px;
        background:#434343;
        display: flex;

    }
    .footer_font{
        padding: 6px 12px;
        color: #8c8b8b;
    }
    
</style>