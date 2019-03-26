<template>
  <div class="section">
    <div class="section_serve">
        <h2>{{before}}</h2>
    </div>
    <div class="section_img">
        <img src="https://www.bestsign.cn/_nuxt/img/5f19b32.jpg" alt="">
    </div>
  </div>
  
</template>

<script>
export default {
  name: "Section",
  data() {
    return {
        before:"电子签约生命周期服务"
    };
  }
};
</script>

<style scoped lang="scss">
    .section{
        width: 319.6px;
        height: 418.95px;
        padding: 50px 10px;
    }
    .section_serve{
        width: 100%;
        height: 77.2px;
     
    }
    .section_serve>h2{
        font-size:24px;
         font-weight: 400;
         padding-bottom:50px; 
         text-align: center;
    }
    .section_img>img{
        width: 349.6px;
        height: 241.75px;
    }

</style>