<template>
  <div class="container">
    <div class="container_top">
      <h2>{{question}}</h2>
    </div>
    <div class="container_img">
      <ul>
        <li v-for="item in imgs">
          <img :src="item.img" alt>
          <p>{{item.title}}</p>
        </li>
        <div class="container_exp">
          <div class="container_bg"></div>
          <div class="container-font">敬请期待</div>
            <img src="../../images/qd.jpg" alt>
            <p>其他</p>
         
        </div>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: "Container",
  data() {
    return {
      question: "为你定制行业专属解决方案",
      imgs: [
        {
          img: "https://www.bestsign.cn/_nuxt/img/2999e7c.jpg",
          title: "供应链金融"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/60f8ae2.jpg",
          title: "智慧物流"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/408d56e.jpg",
          title: "互联网平台"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/3c5fc16.jpg",
          title: "银行保险"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/25b07a0.jpg",
          title: "会联网金融"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/b9550d2.jpg",
          title: "租贷平台"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/bcbd9a7.jpg",
          title: "汽车金融"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/758bf47.jpg",
          title: "零售制造"
        },
        {
          img: "https://www.bestsign.cn/_nuxt/img/d26d0ad.jpg",
          title: "人力资源"
        }
      ]
    };
  }
};
</script>

<style scoped lang="scss">
.container {
  position: relative;
  width: 355px;
  height: 900.2px;
  padding-top: 50px;
  padding-left: 10px;
  padding-bottom: 50px;
}
.container_top {
  width: 100%;
  height: 77.2px;
  padding-bottom: 50px;
}
.container_top > h2 {
  text-align: center;
  font-size: 24px;
  font-weight: 400;
}
.container_img > ul {
  height: 800px;
}
.container_img > ul > li {
  width: 171.6px;
  height: 150px;
  float: left;
  margin-bottom: 15px;
  border-radius: 4px;
  display: block;
  margin-right: 5px;
}
.container_img > ul > li > img {
  width: 100%;
  height: 115px;
}
.container_img > ul > li > p {
  width: 100%;
  height: 35px;

  background: #eee;
  line-height: 35px;
  font-size: 14px;
  text-align: center;
}
.container_exp {
  position: absolute;
  width: 171.6px;
  height: 150px;
  bottom: 14px;
  right: 7px; 
}
.container_bg {
  width: 171.6px;
  height: 150px;
  position: absolute;
  background: black;
  opacity: 0.3; 
}
.container_exp > img {
  width: 171.6px;
  height: 115px;
}
.container_exp>p{
  background: #eee;
  width: 100%;
  height: 35px;  
  text-align: center;
  line-height: 35px;
  font-size: 14px;
}
.container-font{
     width: 172.6px;
     height: 150px;
    position: absolute;
    color: #fff;
     line-height: 150px;
     text-align: center;
     font-size: 16px;
}

</style>