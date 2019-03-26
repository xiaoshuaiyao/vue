<template>
  <div class="top">
    <div class="con">
      <h2>{{concents}}</h2>
    </div>
    <div class="mes">
      <p>{{message}}</p>
    </div>
    <div class="btn">
      <button>{{btn}}</button>
    </div>
    <div class="images">
         <img src="https://www.bestsign.cn/_nuxt/img/d706239.jpg" alt="">
    </div>
   
  </div>
  
</template>

<script>
export default {
  name: "Top",
  data() {
    return {
      concents: "签合同, 上上签一下",
      message: "构建智能时代的契约规则",
      btn: "免费试用"
    };
  }
};
</script>

<style scoped lang="scss">
.top {
  margin-top: 56px;
  width: 100%;
  height: 377.18px;
}
.con {
  padding-top: 75px;
}
.con > h2 {
  font-size: 30px;
  font-weight: 400;
  text-align: center;
}
.mes {
  margin: 15px auto 30px;
}
.mes > p {
  font-size: 14px;
  line-height: 28px;
  color: #888;
  text-align: center;
}
.btn {
  text-align: center;
}
.btn > button {
  width: 150px;
  height: 50px;
  border-radius: 20px;
  border: 0;
  background: #05af9c;
  box-shadow: 0 2px 8px 0 rgba(36, 10, 147, 0.15);
  color: #fff;
  font-weight: 400;
  cursor: pointer;
}
.images{
    height: 146.56px;
}
.images>img{
    height: 146.56px;
    width: 100%;
}
</style>