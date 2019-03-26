<template>
  <div class="nav">
    <div class="nav_nav">
      <ul>
        <li v-for="item in lists">
          {{item}}
          <div class="nav_font">
            <p class="iconfont">&#xe632;</p>
          </div>
        </li>
      </ul>
    </div>
    <div class="copy">
      <div class="copy_top">
        <img src="https://www.bestsign.cn/_nuxt/img/bb0ccd4.png" alt>
      </div>
      <div class="copy_mid">
        <img src="https://www.bestsign.cn/_nuxt/img/ef21c6e.png" alt>
      </div>
      <div class="copy_btm">
        <img src="https://www.bestsign.cn/_nuxt/img/b310b21.jpg" alt>
      </div>
    </div>
    <div class="copy_p">
      <p>{{text}}</p>
    </div>
    <div class="copy_span">
      <span>{{txt}}</span>
    </div>
  </div>
</template>
<script>
export default {
  name: "Nav",
  data() {
    return {
      lists: ["产品", "资源", "上上签", "合作", "24小时热线"],
      text: "浙公网安备 33010602006436号ICP主体备案号 浙ICP备14031930号-1",
      txt: "Copyright © 2014-2019 杭州尚尚签网络科技有限公司"
    };
  }
};
</script>

<style scoped lang="scss">
.nav {
  width: 243.2px;
  height: 430px;
  padding: 0 16px;
}
.nav_nav {
  width: 343.2px;
  height: 48px;
}
.nav_nav > ul > li {
  line-height: 48px;
  font-size: 13px;
  color: #303133;
  border-bottom: 1px solid #ebeef5;
}
.nav_font {
  float: right;
}
.copy {
  margin-top: 200px;
  width: 343.2px;
  height: 60px;
  padding: 10px 0;
  display: flex;
  justify-content: center;
}
.copy > div {
  margin: 10px;
}
.copy_top > img {
  width: 50px;
  height: 39px;
}
.copy_mid > img {
  width: 60px;
  height: 31.2px;
}
.copy_btm > img {
  width: 40px;
  height: 40px;
}
.copy_p > p {
  width: 375px;
  height: 11.2px;
  color: #6e6e6c;
  font-size: 10px;
  text-align: center;
}

.copy_span {
  padding-top: 5px;
  width: 375px;
  height: 11.2px;
  text-align: center;
}

.copy_span > span {
  color: #6e6e6c;
  font-size: 10px;
}
</style>