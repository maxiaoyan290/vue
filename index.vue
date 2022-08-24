<template>

  <div class = "mainn"> 
  <img :src="defaultImg" 
        alt = ""
        class = "rightullidiv"
  />
  <p class = "add">
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}地址：上海市嘉定区曹安公路4800号同济大学嘉定校区
  </p>
  <p class = "nor">
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}开放时间：每周一到周五10点至22点
  </p>


  <p class = "nor">
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}购票链接：
  </p>
  <router-link to="www.baidu.com">{{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}www.baidu.com</router-link>
  <p class = "nor">
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}景区景点介绍：
    <br>
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}本景区是一所风景优美面向各年龄段游客
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}的景点。
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}始建于1998年，月流量超过2W，
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}单日流量最高可达1k。
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}空气新鲜，适合老年人前来活动，
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}并且游乐设施较多，同样适合儿童前来玩耍
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}公园距离地铁三号线较近，交通便利，
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}乘坐999或523线均可到达。
  </p>
      <p class = "nor">
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}门票价格：
    <br>
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}7岁以下儿童：{{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}免票
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}7-14岁儿童：{{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}20
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}14岁及以上群众：{{"\xa0\xa0"}}40
  </p>
      <p class = "nor">
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}联系电话：
    <br>
    <br>
    {{"\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0\xa0"}}198XXXXXXXX
  </p>
  <div class="mask" v-if="showModal" @click="showModal=false">
  </div>
   <div class="pop" v-if="showModal"> 
        <Modal class="mdl">
          <p class = "usr">
            匿名用户_1AFC6B
          </p>
          <p>
            {{"\xa0\xa0"}}假期带女儿来玩，是个放松的好去处。
          </p>
          <p class = "usr">
            匿名用户_34FC90
          </p>
          <p>
            {{"\xa0\xa0"}}适合全家人一起游玩
          </p>
          <p class = "usr">
            匿名用户_9DC03E
          </p>
          <p>
            {{"\xa0\xa0"}}爸妈之前来这里散步，跟我说空气很好。
          </p>
        </Modal>
        <button @click="showModal=false" class="btn">点击关闭</button>
   </div>
   <button @click="showModal=true" class="btn">用户评价</button>
  <br>
  </div>
</template>

<script>
  import deImg  from './h.jpg'
  import Img  from './O.jpg'
  export default {
		data () {
				return {
				 	defaultImg:deImg  ,
          showModal: false  ,
          Imgg : Img
				  }
		 }
}
</script>
<style rel="stylesheet/scss" lang="scss" scoped>
  .rightullidiv {
    border: 1px rgb(158, 16, 16) ridge;
    width: 100%;
    /*background: #f2f2f2;*/
    display: flex;
    justify-content: center;
    align-items: center;
    .rightulliimg {
      max-width: 80%;
      max-height: 500px;
    }
  }
  .mainn{
    background-image: url('./O.jpg');
    background-size: 100%;
  }
  .add{
    color: #000;
    font-size: 10px;
  }
  .nor{
    font-weight:100;
  }
  .mask {
  background-color: #000;
  opacity: 0.3;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1
}
.pop {
  background-image: url('./T.jpg');
  background-size: cover;
  position: fixed;
  top: 85px;
  left: 0;
  width: 100%;
  height:100%;
  z-index: 2
}
.btn {
  position:fixed;
  background-color: #f00;
  border: 1px solid red;
  padding: 100%，20px;
  width:100%;
  height:50px;
  color:yellow;
  font-weight:bold;
  bottom: 0;
}
.mdl {
  width: 100px;
  background-image: url('./R.jpg');
}
.usr{
  font-size: 18px;
  font-weight: bold;
}
</style>