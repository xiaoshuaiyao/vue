<template>
  <div class="nav">
     <div class="nav_nav">
         <ul>
             <li v-for="item in lists">
                    {{item}} 
                <div class="nav_font"><p class="iconfont">&#xe632;
</p></div>                    
             </li>
         </ul>
     </div>
  </div>
  
</template>

<script>
export default {
  name: "Nav",
  data() {
    return {
         lists:["产品","资源","上上签","合作","24小时热线"]
    };
  }
};
</script>

<style scoped lang="scss">
    .nav{
        width: 243.20px;
        height: 383.6px;
        padding: 0 16px;
    }
    .nav_nav{
        width: 343.2px;
        height: 48px;
       
    }
    .nav_nav>ul>li{
        
        line-height: 48px;
        font-size: 13px;
        color: #303133;
        border-bottom: 1px solid #ebeef5;
    }
    .nav_font{
        float: right;
    }
    
</style>