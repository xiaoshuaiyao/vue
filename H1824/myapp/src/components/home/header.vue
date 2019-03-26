<template>
  <div class="header">
    <div class="header_left">
      <img src="../../images/bg.png" alt>
    </div>
    <div class="header_right">
      <span class="iconfont">&#xe606;</span>
    </div>
    <ul class="header_dis">
      <li v-for="(item,index) in diss">{{item}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header",
  data(){
    return{
        diss:["产品","解决方案","客户案例","服务中心"]
    }
  }
};
</script>

<style scoped lang="scss">
.header {
  position: fixed;
  left: 0;
  top: 0;
  display: flex;
  width: 100%;
  height: 56px;
  justify-items: center;
  padding: 0 20px;
  align-items: center;
}
.header_left {
  width: 250px;
  height: 56px;
}
.header_left > img {
  width: 120px;
  height: 42px;
  padding: 5px;
}
.header_right {
  width: 93px;
  height: 56px;
  display: flex;
  align-items: center;
}
.header_right > span {
  color: green;
  margin-left: 60px;
}
.header_dis{
  position: absolute;
  width: 100%;
  height: 200px;
  left: 0;
  top: 56px;
  margin: 20px;
}
.header_dis{
  line-height: 30px;
}
</style>
