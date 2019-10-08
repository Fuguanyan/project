<template>
  <div>
    <div class="hader">
      <div class="hader-img">
        <img src="../../static/img/4.png" alt />
      </div>
      <div class="hader-list">
        <ul>
          <a href>
            <li>萨克斯智能录音棚</li>
          </a>
          <a href="#D">
            <li>萨克斯电子弱音器</li>
          </a>
          <a href="#E">
            <li>智能萨克斯APP</li>
          </a>
          <a href="#G" class="a">
            <li>升级计划</li>
          </a>
          <a href class="_a">
            <li>其他产品</li>
          </a>
        </ul>
      </div>
      <div class="hader-bnt" @click="btn">
        <button>立刻购买</button>
      </div>
    </div>
    <div class="wrapper">
      <div class="wrapper-title">
        <div class="wrapper-A">
          <p>SMART SAX PARTNER</p>
          <P>萨克斯智能录音棚</P>
        </div>
        <div class="wrapper-B">
          <p>你的私家录音棚现已上线</p>
        </div>
        <div class="wrapper-C" @click="add">
          <button>了解详情</button>
        </div>
      </div>
    </div>
    <div class="content" id="D">
      <div class="content-title">
        <div class="content-A">
          <p>智慧系统，智能调节</p>
        </div>
        <div class="content-B">
          <p>告别陈旧的录制体验，经由Smart Play OS的控制，您的音色，音效被科技重新演绎， 将智能科技注入音乐，您的演奏体验从此进化。</p>
        </div>
        <div class="content-C">
          <div class="show" v-if="show">
            <p>Music Processing Core</p>
            <p>高性能的CPU为音乐的数字化实时合成提供了充分的性能保障，这是过往纯录音产品无法比拟的。</p>
          </div>
          <div class="_content-img">
            <div class="_img">
              <img src="../../static/img/20.png" alt />
            </div>
            <div class="_content-text">
              <p>音量调节</p>
            </div>

            <div class="_content-btn">
              <button  @click="tiaojie">了解详情</button>
            </div>
          </div>
          <div class="_content-img">
            <div class="_img">
              <img src="../../static/img/23.png" alt />
            </div>
            <div class="_content-text">
              <p>混响调节</p>
            </div>

            <div class="_content-btn">
              <button  @click="tiaojie">了解详情</button>
            </div>
          </div>
          <div class="_content-img">
            <div class="_img">
              <img src="../../static/img/24.png" alt />
            </div>
            <div class="_content-text">
              <p>音色调节</p>
            </div>
            <div class="_content-btn">
              <button  @click="tiaojie">了解详情</button>
            </div>
          </div>
        </div>

        <div class="content-D">
          <div class="content-D-img">
            <div class="_img">
              <img src="../../static/img/26.png" alt />
            </div>
            <div class="content-D-text">
              <p>数字均衡器</p>
            </div>
            <div class="content-D-btn">
              <button>了解详情</button>
            </div>
          </div>
          <div class="content-D-img">
            <div class="_img">
              <img src="../../static/img/27.png" alt />
            </div>
            <div class="content-D-text">
              <p>电子节拍器</p>
            </div>
            <div class="content-D-btn">
              <button>了解详情</button>
            </div>
          </div>
          <div class="content-D-img">
            <div class="_img">
              <img src="../../static/img/28.png" alt />
            </div>
            <div class="content-D-text">
              <p>电子校音器</p>
            </div>
            <div class="content-D-btn">
              <button>了解详情</button>
            </div>
          </div>
          <div class="content-D-img">
            <div class="_img">
              <img src="../../static/img/29.png" alt />
            </div>
            <div class="content-D-text">
              <p>乐曲和伴奏</p>
            </div>
            <div class="content-D-btn">
              <button>了解详情</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="list">
      <div class="list-title">
        <p>強勁“芯”能力，奏響新境界</p>
        <p>ARM专业级芯片</p>
        <p>高清硬解码，还原纯粹音质。分分秒秒，让节奏恰如其分。</p>
      </div>
      <div class="list-footer">
        <div class="footer-A">
          <div class="footer-img">
            <img src="../../static/img/30.png" alt />
          </div>
          <div class="footer-text">
            <p>Music Core</p>
          </div>
          <div class="footer-btn">
            <button>了解详情</button>
          </div>
        </div>
        <div class="footer-A">
          <div class="footer-img">
            <img src="../../static/img/30.png" alt />
          </div>
          <div class="footer-text">
            <p>IPS全触屏</p>
          </div>
          <div class="footer-btn">
            <button>了解详情</button>
          </div>
        </div>
        <div class="footer-A">
          <div class="footer-img">
            <img src="../../static/img/30.png" alt />
          </div>
          <div class="footer-text">
            <p>IPS全触屏</p>
          </div>
          <div class="footer-btn">
            <button>了解详情</button>
          </div>
        </div>
      </div>
    </div>
    <div class="between">
      <div class="between-text">
        <p>弹指间，直觉操控</p>
        <p>ARM 专业级CPU，秒秒分分，让节奏恰如其分；</p>
        <p>6G超高速存储，海量乐曲放心存，随心播，大容量电池保证您一整天的使用</p>
      </div>
    </div>
    <div class="between-B">
      <div class="B-text">
        <p>采音干净，才有音乐的纯净</p>
        <p>从频响曲线着手，经过音频工程师的重重测试和优化，</p>
        <p>最终定制出专用的麦克风，尽可能多的采集到原始声音数据，利于后期调整。</p>
      </div>
    </div>
    <div class="between-C">
      <div class="C-text">
        <p>录音棚 同级设计</p>
        <p>契合腔体设计</p>
        <p>高品质环保ABS材料制造</p>
        <p>国际一线声效大厂同款滤音海绵</p>
      </div>
    </div>
    <div class="between-D">
      <div class="D-textA">
        <p>柔软的表象之下，饱含硬核科技</p>
      </div>
      <div class="D-textB">
        <p>多孔海绵，吸收声波，减少声波回弹（回声），让采集的声音更干净。 同时由于大部分声音被吸收，从而达到理想的降噪效果。</p>
      </div>
    </div>
    <div class="between-E" id="E">
      <div class="_between">
        <div class="E-textA">
          <p>Smart Sax App</p>
        </div>
        <div class="E-textB">
          <p>海量乐曲，随心伴奏</p>
          <p>搭配硬件使用，操作更方便，还能与硬件同步调音数据</p>
        </div>
      </div>
    </div>
    <div class="between-F">
      <div class="F-img">
        <img src="../../static/img/Arrow.png" alt />
        <img src="../../static/img/Arrow (1).png" alt />
      </div>
      <div class="F-box"></div>
      <div class="F-boxB"></div>
      <div class="F-title">
        <p>KOGI MOTOFUMI</p>
        <p>独立音乐制作人</p>
      </div>
      <div class="F-content">Seaboard Block 是一款强大的便携式控制器，既可以独立工作，也可连接到 BLOCKS 模块化系统的其他 Blocks。</div>
    </div>
    <div class="between-G" id="G">
      <div class="G-text">
        <p>焕然“芯”升，迎接全新演奏体验</p>
        <p>只需2680元，即可从弱音器升级到智能录音棚， 老客户更只需1680元，即可获得前所未有的演奏体验。</p>
        <button>了解详情</button>
      </div>
    </div>
    <div class="between-H">
      <div class="H-left">
        <img src="../../static/img/4.png" alt />
      </div>
      <div class="H-textA">
        <a href>
          <p>智能录音棚</p>
        </a>
        <a href>
          <p>APP</p>
        </a>
      </div>
      <div class="H-textB">
        <a href>
          <p>技术支持</p>
        </a>
        <a href>
          <p>联系我们</p>
        </a>
        <a href>
          <p>关于威柏仕</p>
        </a>
      </div>
      <div class="H-textC">
        <a href>
          <p>法规条款及细则</p>
        </a>
        <a href>
          <p>隐私政策</p>
        </a>
      </div>
      <div class="H-right">
      <a href="">
         <img src="../../static/img/Facebook.png" alt />
      </a>
       <a href="">
         <img src="../../static/img/G+.png" alt />
       </a>
        <a href="">
            <img src="../../static/img/Instagram.png" alt />
        </a>
        <a href="">
           <img src="../../static/img/Twitter.png" alt />
        </a>
       
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
      show: false
    };
  },
  methods: {
    btn: function() {
      alert("功能完善中");
    },
    add: function() {
      alert("功能稍后开发，敬请期待");
    },
    
   tiaojie: function () {
     alert("资料完善中")
     console.log(111)
   }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0;
  padding: 0;
  list-style: none;
}
.hader {
  background: #030303;
  width: 100%;
  height: 80px;
  display: flex;
  flex: 1;
  justify-content: space-around;
  align-items: center;
  border: 1px dashed #888888;
}
.hader-img {
  /* border: 1px solid blue; */
  height: 42px;
  width: 42px;
}
@media screen and (max-width: 420px) {
  
 .hader .hader-list ul .a {
   display: none;
 }
 .hader .hader-list ul ._a{
   display: none;
 }
 .hader .hader-bnt button {
  width: 65px;
  height: 30px;
  border-radius: 50px;
  letter-spacing: 1px;
  background: #2c71da;
  color: rgba(255, 255, 255, 1);
  font-size: 12px;
}
.hader .hader-list{
  margin-left: 50px;
}

 
}
.hader-img image {
  height: 100%;
  width: 100%;
}
.hader-list {
  display: flex;
  /* flex-direction: row; */
  justify-content: center;
  align-items: center;
  width: 1160px;
  height: 20px;
  /* border: 1px solid red; */
  color: #ffffff;
}

.hader-list li {
  display: inline-block;
  font-size: 14px;
  line-height: 24px;
  color: rgba(255, 255, 255, 1);
  font-family: PingFang SC;
  margin: 0 30px;
}
.hader-bnt {
  /* border: 1px solid aqua; */
  width: 120px;
  height: 35px;
  /* border-radius: 50px; */
  /* text-align: center;
  line-height: 35px; */
}
button {
  outline: none;
}
.hader-bnt button {
  width: 100%;
  height: 100%;
  border-radius: 50px;
  letter-spacing: 5px;
  background: #2c71da;
  color: rgba(255, 255, 255, 1);
}
.wrapper {
  background: url("../../static/img/1.png") no-repeat center;
  /* border: 1px solid brown; */
  height: 1100px;
  width: 100%;
  position: relative;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .wrapper {
    background: url("../../static/img/1.png") no-repeat center;
    background-size: cover;
    height: 375px;
    width: 100%;
    margin-top: 0;
  }
  .wrapper .wrapper-title {
    display: flex;
    flex-direction: column;
    height: 320px;
    width: 185px;
    position: absolute;
    top: 30%;
    left: 50%;
    transform: translate(-50%, -30%);
    /* border: 1px solid yellow; */
  }
  .wrapper .wrapper-A {
    text-align: center;
    line-height: 48px;
    height: 48px;
    width: 185px;
    /* border: 1px solid beige; */
    font-size: 12px;
    font-family: Noyh;
    font-weight: bold;
    /* line-height: 28px; */
    color: rgba(255, 255, 255, 1);
    margin-top: 0;
  }

  .wrapper .wrapper-B {
    font-size: 16px;
    height: 85px;
    width: 185px;

    text-align: center;
    /* line-height: 72px; */
    font-family: PingFang SC;
    font-weight: 600;
    color: rgba(255, 255, 255, 1);
    opacity: 1;
    margin-top: 48px;
    margin-bottom: 30px;
    /* border: 1px solid red; */
  }
  .wrapper .wrapper-C button {
    height: 45px;
    width: 110px;
    margin: 10px 50px;
    border-radius: 50px;
    background: #2c71da;
    /* color: #ffffff; */
    letter-spacing: 2px;
    font-size: 12px;
    /* font-weight: 200; */
    /* line-height: 36px; */
    color: rgba(255, 255, 255, 1);
  }
}

.wrapper-title {
  display: flex;

  flex-direction: column;
  height: 457px;
  width: 457px;
  position: absolute;
  top: 30%;
  left: 50%;
  transform: translate(-50%, -30%);
  /* border: 1px solid yellow; */
}
.wrapper-A {
  text-align: center;
  line-height: 48px;
  height: 48px;
  width: 457px;
  /* border: 1px solid beige; */
  font-size: 18px;
  font-family: Noyh;
  font-weight: bold;
  line-height: 28px;
  color: rgba(255, 255, 255, 1);
  margin-top: 50px;
}
.wrapper-B {
  height: 166px;
  width: 427px;
  font-size: 50px;
  text-align: center;
  line-height: 72px;
  font-family: PingFang SC;
  font-weight: 500;
  color: rgba(255, 255, 255, 1);
  opacity: 1;
  margin-top: 48px;
}
.wrapper-C {
  /* border: 1px solid blue; */
  height: 60px;
  width: 240px;
  margin: 0 auto;
}
.wrapper-C button {
  height: 100%;
  width: 100%;
  margin: 0 10px;
  border-radius: 50px;
  background: #2c71da;
  /* color: #ffffff; */
  letter-spacing: 5px;
  font-size: 26px;
  font-weight: 500;
  line-height: 36px;
  color: rgba(255, 255, 255, 1);
}

.content {
  position: relative;
  width: 100%;
  height: 2000px;
  background: url("../../static/img/2.png") no-repeat center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  #D {
    background: url("../../static/img/2.png") no-repeat center;
    background-size: cover;
    height: 700px;
    width: 100%;
    /* border: 1px solid blue; */
    margin-top: 0;
  }
  .content .content-title {
    /* border: 1px solid red; */
    height: 350px;
    width: 100%;
    /* margin-bottom:92px; */
    /* margin-top: 30px; */
  }
  .content .content-A {
    /* border: 1px solid blue */
    width: 155px;
    height: 35px;
    font-size: 16px;
    margin-top: 120px;
    line-height: 35px;
    margin-left: 125px;
  }

  .content .content-B {
    font-size: 12px;
    /* border: 1px solid black; */
    width: 100%;
    margin-top: 0;
  }
  .content .content-B p {
    /* border: 1px solid red; */
    padding: 0 20px;
  }
  .content ._content-img {
    /* border: 1px solid yellow; */
    width: 95px;
    height: 152px;
    display: flex;
    flex-direction: column;
    margin-left: 25px;
    margin-top: -25px;
  }
  .content ._content-text {
    font-size: 12px;
  }
  .content .content-D-img {
    display: none;
  }

  .content .content-D-text {
    /* margin-bottom: 20px; */
  }
  .content .content-D-text p {
  }
  .content ._img {
    /* border: 1px solid red; */
    height: 25px;
    width: 25px;
  }
  .content ._img img {
    height: 100%;
    width: 100%;
    /* border: 1px solid yellow; */
  }
  .content ._content-btn {
  }
  .content ._content-btn button {
    /* border: 1px solid red; */
    height: 25px;
    width: 55px;
    font-size: 11px;
    /* display: none; */
    letter-spacing: 0;
    margin: 0 20px;
  }
}
.content-title {
  position: absolute;
  left: 50%;
  bottom: 5%;
  transform: translate(-50%, -5%);

  height: 657px;
  width: 1160px;
  /* border: 1px solid red; */
}
.content-A {
  width: 1160px;
  height: 90px;
  /* border: 1px solid blue; */
  text-align: center;
  font-size: 60px;
  font-weight: 600;
  line-height: 90px;
  color: rgba(28, 28, 28, 1);
  opacity: 1;
}
.content-B {
  height: 96px;
  width: 1160px;
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 500;
  line-height: 36px;
  color: rgba(28, 28, 28, 1);
  opacity: 1;
  justify-content: center;
  text-align: center;

  margin-top: 20px;
  /* text-align: center; */
  /* border: 1px solid yellowgreen; */
}
.content-B p {
  padding: 10px 30px;
}
.content-C {
  /* border: 1px solid red; */
  width: 1160px;
  height: 226px;
  margin-top: 20px;
  display: flex;
  /* justify-content:space-between; */
}

._content-img {
  /* border: 1px solid blue; */
  display: flex;
  flex-direction: column;
  height: 220px;
  width: 135px;
  align-items: center;
  /* padding: 0 120px; */
  margin-left: 190px;
  /* margin: 0 auto; */
}
._img {
  /* border: 1px solid red; */
  height: 57px;
  width: 57px;
  margin: 20px 0;
}
._img image {
  height: 100%;
  width: 100%;
}
._content-text {
  margin-bottom: 20px;
  font-size: 18px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 28px;
  color: rgba(0, 0, 0, 1);
}
._content-btn {
  width: 100px;
  height: 40px;
}
._content-btn button {
  width: 100px;
  height: 40px;
  border: 1px solid rgba(0, 0, 0, 0.5);
  opacity: 1;
  border-radius: 20px;
  letter-spacing: 5px;
}
.content-D {
  width: 1260px;
  height: 250px;
  display: flex;
  /* justify-content: space-between; */

  /* border: 1px solid black; */
}
.content-D-img {
  width: 110px;
  height: 220px;
  /* border: 1px solid yellowgreen; */
  margin: 0 95px;
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  align-items: center;
}
/* .content-D-img image{
  height: 100%;
  width: 100%;
} */
.content-D-text {
  margin-bottom: 20px;
}
.content-D-text p {
  width: 90px;
  height: 25px;
  font-size: 18px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 25px;
  color: rgba(0, 0, 0, 1);
}
.content-D-btn {
}
.content-D-btn button {
  width: 100px;
  height: 40px;
  border: 1px solid rgba(0, 0, 0, 0.5);
  opacity: 1;
  border-radius: 20px;
  letter-spacing: 5px;
}
.list {
  position: relative;
  width: 100%;
  height: 1160px;
  /* margin-top:20px; */
  background: url("../../static/img/5.png") no-repeat center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .list {
    position: relative;
    background: url("../../static/img/5.png") no-repeat center;
    width: 100%;
    height: 700px;
  }
  .list .list-title {
    position: absolute;
    top: 10%;
    left: 50%;
    transform: translate(-50%, -10%);
  }
  .list .list-title p:nth-of-type(1) {
    width: 100%;
    height: 60px;
    /* border: 1px solid blue; */
    font-family: PingFang SC;
    font-size: 20px;
    /* font-weight: 600; */
    line-height: 60px;
    color: rgba(255, 255, 255, 1);
    text-shadow: 0px 3px 6px rgba(0, 0, 0, 0.16);
    text-align: center;
  }
  .list .list-title p:nth-of-type(2) {
    width: 370px;
    height: 40px;
    font-size: 16px;
    font-family: PingFang SC;
    /* font-weight: 600; */
    line-height: 45px;
    color: rgba(255, 255, 255, 1);
    opacity: 1;
    text-align: center;

    /* border: 1px solid red; */
  }
  .list .list-title p:nth-of-type(3) {
    width: 100%;
    height: 20px;
    font-size: 14px;
    line-height: 20px;
    font-family: PingFang SC;
    /* font-weight: 600; */
    color: rgba(255, 255, 255, 1);
    opacity: 1;
    text-align: center;
    /* border: 1px solid blue; */
  }
  .list .list-footer {
    /* border: 1px solid floralwhite; */
    height: 135px;
    width: 100%;
    position: absolute;
    display: flex;
    justify-content: space-between;
    left: 50%;
    bottom: 5%;
    transform: translate(-50%, -10%);
  }
  .list .footer-A {
    /* border: 1px solid red; */
    width: 110px;

    display: flex;
    flex-direction: column;
    text-align: center;
  }
  .list .footer-text {
    margin-top: 10px;
    width: 110px;
    height: 25px;
    /* border: 1px solid forestgreen; */
  }
  .list .footer-text p {
    width: 100%;
    height: 100%;
    font-size: 12px;
    font-family: PingFang SC;
    font-weight: 400;
    line-height: 25px;
    color: rgba(255, 255, 255, 1);
  }
  .list .footer-btn {
    margin-top: 20px;
  }
  .list .footer-btn button {
    width: 65px;
    height: 25px;
    /* border: 1px solid rgba(255, 255, 255, 0.5); */
    opacity: 1;
    border-radius: 20px;
    font-size: 10px;
    font-family: PingFang SC;

    text-align: center;
    line-height: 17px;
    letter-spacing: 0;
    /* color: rgba(255, 255, 255, 1); */
  }
  .list .footer-img {
    height: 35px;
    width: 35px;
    /* border: 1px solid blue; */
    margin-left: 40px;
  }
  .list .footer-img img {
    height: 100%;
    width: 100%;
  }
}

.list-title {
  position: absolute;
  top: 10%;
  left: 50%;
  transform: translate(-50%, -10%);
}
.list-title p:nth-of-type(1) {
  width: 1160px;
  height: 90px;
  /* border: 1px solid blue; */
  font-family: PingFang SC;
  font-size: 60px;
  font-weight: 600;
  line-height: 90px;
  color: rgba(255, 255, 255, 1);
  text-shadow: 0px 3px 6px rgba(0, 0, 0, 0.16);
  text-align: center;
}
.list-title p:nth-of-type(2) {
  width: 1159px;
  height: 86px;
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 86px;
  color: rgba(255, 255, 255, 1);
  opacity: 1;
  text-align: center;

  /* border: 1px solid red; */
}
.list-title p:nth-of-type(3) {
  width: 1159px;
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  color: rgba(255, 255, 255, 1);
  opacity: 1;
  text-align: center;
  /* border: 1px solid blue; */
}
.list-footer {
  /* border: 1px solid floralwhite; */
  height: 155px;
  width: 526px;
  position: absolute;
  display: flex;
  justify-content: space-between;
  left: 50%;
  bottom: 5%;
  transform: translate(-50%, -10%);
}
.footer-A {
  /* border: 1px solid red; */
  width: 110px;

  display: flex;
  flex-direction: column;
  text-align: center;
}
.footer-text {
  margin-top: 10px;
  width: 110px;
  height: 25px;
  /* border: 1px solid forestgreen; */
}
.footer-text p {
  width: 100%;
  height: 100%;
  font-size: 18px;
  font-family: PingFang SC;
  font-weight: 400;
  line-height: 25px;
  color: rgba(255, 255, 255, 1);
}
.footer-btn {
  margin-top: 20px;
}
.footer-btn button {
  width: 100px;
  height: 40px;
  border: 1px solid rgba(255, 255, 255, 0.5);
  opacity: 1;
  border-radius: 20px;
  font-size: 12px;
  font-family: PingFang SC;
  font-weight: 600;
  text-align: center;
  line-height: 17px;
  letter-spacing: 5px;
  /* color: rgba(255, 255, 255, 1); */
}
.between {
  position: relative;
  background: url("../../static/img/10.png") no-repeat center;
  height: 1160px;
  width: 100%;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .between {
    position: relative;
    background: url("../../static/img/10.png") no-repeat center;
    background-size: cover;
    height: 750px;
    width: 100%;
  }
  .between .between-text p:nth-of-type(1) {
    height: 30px;
    width: 100%;
    font-size: 18px;
    font-family: PingFang SC;

    line-height: 30px;
    text-align: center;
    color: rgba(255, 255, 255, 1);
    text-shadow: 0px 3px 6px rgba(32, 25, 25, 0.16);
    /* border: 1px solid red; */
    margin-top: 50px;
  }
  .between .between-text p:nth-of-type(2) {
    width: 100%;
    height: 30px;
    /* border: 1px solid blanchedalmond; */
    font-size: 12px;
    font-family: PingFang SC;

    color: rgba(255, 255, 255, 1);
    text-align: center;
    /* line-height: 30px; */
    margin-top: 20px;
  }
  .between .between-text p:nth-of-type(3) {
    width: 370;
    height: 20px;
    /* border: 1px solid blanchedalmond; */
    font-size: 11px;
    font-family: PingFang SC;

    color: rgba(255, 255, 255, 1);
    text-align: center;
    line-height: 20px;
    /* padding: 0 10px; */
  }
  .between-text {
    position: absolute;
    left: 50%;

    transform: translate(-50%);
  }
}
.between p:nth-of-type(1) {
  height: 90px;
  width: 1160px;
  font-size: 60px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 90px;
  text-align: center;
  color: rgba(255, 255, 255, 1);
  text-shadow: 0px 3px 6px rgba(32, 25, 25, 0.16);
  /* border: 1px solid red; */
  margin-top: 120px;
}
.between p:nth-of-type(2) {
  width: 1159px;
  height: 43px;
  /* border: 1px solid blanchedalmond; */
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;

  color: rgba(255, 255, 255, 1);
  text-align: center;
  line-height: 43px;
  margin-top: 20px;
}
.between p:nth-of-type(3) {
  width: 1159px;
  height: 43px;
  /* border: 1px solid blanchedalmond; */
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;

  color: rgba(255, 255, 255, 1);
  text-align: center;
  line-height: 43px;
}
.between-text {
  position: absolute;
  left: 50%;

  transform: translate(-50%);
}
.between-B {
  position: relative;
  height: 1160px;
  width: 100%;
  background: url("../../static/img/35.png") no-repeat center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .between-B {
    position: relative;
    height: 700px;
    width: 100%;
    background: url("../../static/img/35.png") no-repeat center;
    background-size: cover;
  }
  .B-text {
    position: absolute;
    left: 50%;
    bottom: 10%;
    transform: translate(-50%, -10%);
  }
  .between-B .B-text p:nth-of-type(1) {
    height: 90px;
    width: 100%;
    font-size: 22px;
    font-family: PingFang SC;

    line-height: 90px;
    text-align: center;
    color: rgba(255, 255, 255, 1);
    text-shadow: 0px 3px 6px rgba(32, 25, 25, 0.16);
    /* border: 1px solid red; */
    margin-top: 120px;
  }
  .between-B .B-text p:nth-of-type(2) {
    width: 1159px;
    height: 43px;
    /* border: 1px solid blanchedalmond; */
    font-size: 13px;
    font-family: PingFang SC;

    color: rgba(255, 255, 255, 1);
    text-align: center;
    line-height: 43px;
    margin-top: 20px;
  }
  .between-B .B-text p:nth-of-type(3) {
    width: 350px;
    height: 30px;
    /* border: 1px solid blanchedalmond; */
    font-size: 10px;
    font-family: PingFang SC;
    margin-left: 400px;
    line-height: 30px;

    color: rgba(255, 255, 255, 1);
    text-align: center;
  }
}

.B-text {
  position: absolute;
  left: 50%;
  bottom: 10%;
  transform: translate(-50%, -10%);
}
.B-text p:nth-of-type(1) {
  height: 90px;
  width: 1160px;
  font-size: 60px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 90px;
  text-align: center;
  color: rgba(255, 255, 255, 1);
  text-shadow: 0px 3px 6px rgba(32, 25, 25, 0.16);
  /* border: 1px solid red; */
  margin-top: 120px;
}
.B-text p:nth-of-type(2) {
  width: 1159px;
  height: 43px;
  /* border: 1px solid blanchedalmond; */
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;

  color: rgba(255, 255, 255, 1);
  text-align: center;
  line-height: 43px;
  margin-top: 20px;
}
.B-text p:nth-of-type(3) {
  width: 1159px;
  height: 43px;
  /* border: 1px solid blanchedalmond; */
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;

  color: rgba(255, 255, 255, 1);
  text-align: center;
  line-height: 43px;
}
.between-C {
  position: relative;
  width: 100%;
  height: 1400px;
  background: url("../../static/img/6.png") no-repeat center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .between-C {
    position: relative;
    width: 100%;
    height: 410px;
    background: url("../../static/img/6.png") no-repeat center;
    background-size: cover;
  }
  .between-C .C-text {
    position: absolute;
    top: 30%;
    left: 15%;

    transform: translate(-25%, -30%);
    /* border: 1px solid red; */
    width: 90px;
    height: 410px;
  }
  .between-C .C-text p:nth-of-type(1) {
    font-size: 20px;
    font-family: PingFang SC;
    height: 35px;
    width: 85px;
    line-height: 35px;

    color: rgba(255, 255, 255, 1);

    /* border: 1px solid floralwhite; */
  }
  .between-C .C-text p:nth-of-type(2) {
    font-family: PingFang SC;
    height: 35px;
    width: 85px;
    font-size: 13px;
    padding: 0;
    margin: 0;

    color: rgba(255, 255, 255, 1);

    /* border: 1px solid floralwhite; */
  }
  .between-C .C-text p:nth-of-type(3) {
    font-family: PingFang SC;
    height: 35px;
    width: 85px;
    font-size: 13px;

    /* border: 1px solid blanchedalmond; */
    color: rgba(255, 255, 255, 1);
    /* margin-top: 20px; */
  }
  .between-C .C-text p:nth-of-type(4) {
    font-size: 13px;
    font-family: PingFang SC;

    width: 230px;
    height: 31px;

    line-height: 22px;
    /* border: 1px solid blanchedalmond; */

    color: rgba(255, 255, 255, 1);
    margin-top: 140px;
    line-height: 30px;
  }
}
.C-text {
  position: absolute;
  top: 30%;
  left: 25%;

  transform: translate(-25%, -30%);
  /* border: 1px solid red; */
  width: 250px;
  height: 850px;
}
.C-text p:nth-of-type(1) {
  font-size: 60px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 72px;
  color: rgba(255, 255, 255, 1);
  margin-bottom: 80px;
  /* border: 1px solid floralwhite; */
}
.C-text p:nth-of-type(2) {
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  width: 230px;
  height: 120px;
  color: rgba(255, 255, 255, 1);
  padding-top: 70px;
  /* border: 1px solid floralwhite; */
  line-height: 120px;
}
.C-text p:nth-of-type(3) {
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  width: 230px;
  height: 120px;
  margin-top: 50px;
  color: rgba(255, 255, 255, 1);
  /* margin-top: 20px; */
}
.C-text p:nth-of-type(4) {
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  width: 230px;
  height: 120px;
  margin-top: 50px;
  color: rgba(255, 255, 255, 1);
  /* margin-top: 20px; */
}
.between-D {
  position: relative;
  width: 100%;
  height: 900px;
  background: url("../../static/img/9.png") no-repeat center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .between-D {
    position: relative;
    width: 100%;
    height: 400px;
    background: url("../../static/img/9.png") no-repeat center;
    background-size: cover;
  }

  .between-D .D-textA {
    position: absolute;
    left: 50%;
    top: 30%;
    transform: translate(-50%, -50%);
    width: 100%;
    height: 20px;
    /* border: 1px solid red; */
    font-size: 20px;
    font-family: PingFang SC;
    line-height: 20px;

    color: rgba(255, 255, 255, 1);
    text-align: center;
  }
  .between-D .D-textB {
    position: absolute;
    left: 50%;
    top: 40%;
    transform: translate(-50%, -50%);
    width: 100%;
    height: 96px;
    font-size: 13px;
    font-family: PingFang SC;

    color: rgba(255, 255, 255, 1);
    text-align: center;

    opacity: 1;
    /* border: 1px solid blue; */
    margin-top: 20px;
  }
}

.D-textA {
  position: absolute;
  left: 50%;
  top: 30%;
  transform: translate(-50%, -50%);
  width: 985px;
  height: 90px;
  /* border: 1px solid red; */
  font-size: 60px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 62px;
  color: rgba(255, 255, 255, 1);
  text-align: center;
}
.D-textB {
  position: absolute;
  left: 50%;
  top: 40%;
  transform: translate(-50%, -50%);
  width: 985px;
  height: 96px;
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 36px;
  color: rgba(255, 255, 255, 1);
  text-align: center;

  opacity: 1;
  /* border: 1px solid blue; */
}
.between-E {
  position: relative;
  width: 100%;
  height: 1600px;
  background: url("../../static/img/7.png") no-repeat center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .between-E {
    position: relative;
    width: 100%;
    height: 450px;
    background: url("../../static/img/7.png") no-repeat center;
    background-size: cover;
  }
  .between-E ._between {
    /* border: 1px solid blue; */
    position: absolute;
    top: 20px;
    left: 50%;
    /* transform: translate(-50%); */
  }
  .between-E .E-textA {
    width: 100%;
    height: 20px;
    /* border: 1px solid red; */
    margin-top: -135px;
    line-height: 20px;

    font-size: 18px;
    font-family: Noyh;
    font-weight: bold;

    color: rgba(255, 255, 255, 1);
    text-align: center;
  }
  .between-E .E-textB {
    width: 750px;
    height: 40px;
    /* border: 1px solid blue; */
    margin: 0 auto;
    font-size: 14px;
    font-family: PingFang SC;

    color: rgba(255, 255, 255, 1);
    /* text-align: center; */
  }
}
.between-E ._between {
  /* border: 1px solid blue; */
  position: absolute;
  top: 150px;
  left: 50%;
  transform: translate(-50%);
}
.E-textA {
  width: 1160px;
  height: 80px;
  /* border: 1px solid red; */
  margin-bottom: 30px;

  font-size: 60px;
  font-family: Noyh;
  font-weight: bold;
  line-height: 72px;
  color: rgba(255, 255, 255, 1);
  text-align: center;
}
.E-textB {
  width: 1160px;
  height: 78px;
  /* border: 1px solid blue; */
  margin: 0 auto;
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 36px;
  color: rgba(255, 255, 255, 1);
  text-align: center;
}
.between-F {
  position: relative;
  width: 100%;
  height: 420px;
  background: #101010;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .between-F {
    position: relative;
    width: 100%;
    height: 210px;
    background: #101010;
  }
  .between-F .F-img {
    height: 200px;
    width: 100%;
    margin: 0 auto;
    /* border: 1px solid red; */
  }
  .between-F .F-img img:nth-of-type(2) {
    float: right;
    /* margin: 170px 220px; */
    display: none;
  }
  .between-F .F-img img:nth-of-type(1) {
    /* margin: 170px 220px; */
    display: none;
  }
  .between-F .F-box {
    height: 65px;
    width: 65px;
    border-radius: 50%;
    background: #d8d8d8;
    position: absolute;
    top: 60px;
    left: 20px;
  }
  .between-F .F-boxB {
    height: 28px;
    width: 28px;
    border-radius: 50%;
    background: #d8d8d8;
    position: absolute;
    top: 125px;
    left: 105px;
  }
  .between-F .F-title {
    width: 122px;
    height: 14px;
    position: absolute;
    top: 125px;
    left: 152px;
  }
  .F-title p {
    font-size: 12px;
    font-family: PingFang SC;
    font-weight: 400;
    line-height: 17px;
    color: rgba(101, 107, 111, 1);
  }
  .between-F .F-content {
    width: 290px;
    height: 50px;
    font-size: 13px;
    font-family: PingFang SC;

    line-height: 18px;
    color: rgba(255, 255, 255, 1);
    opacity: 1;
    /* border: 1px solid blue; */
    position: absolute;
    top: 65px;
    left: 95px;
  }
}
.F-img {
  height: 400px;
  width: 1817px;
  margin: 0 auto;
  /* border: 1px solid red; */
}
.F-img img:nth-of-type(2) {
  float: right;
  margin: 170px 220px;
}
.F-img img:nth-of-type(1) {
  margin: 170px 220px;
}
.F-box {
  height: 150px;
  width: 150px;
  border-radius: 50%;
  background: #d8d8d8;
  position: absolute;
  top: 110px;
  left: 364px;
}
.F-boxB {
  height: 32px;
  width: 32px;
  border-radius: 50%;
  background: #d8d8d8;
  position: absolute;
  top: 276px;
  left: 584px;
}
.F-title {
  width: 122px;
  height: 14px;
  position: absolute;
  top: 276px;
  left: 635px;
}
.F-title p {
  font-size: 12px;
  font-family: PingFang SC;
  font-weight: 400;
  line-height: 17px;
  color: rgba(101, 107, 111, 1);
}
.F-content {
  width: 705px;
  height: 139px;
  font-size: 32px;
  font-family: PingFang SC;
  font-weight: 400;
  line-height: 45px;
  color: rgba(255, 255, 255, 1);
  opacity: 1;
  /* border: 1px solid blue; */
  position: absolute;
  top: 110px;
  left: 630px;
}
.between-G {
  width: 100%;
  height: 1000px;
  background: url("../../static/img/8.png") no-repeat center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
  .between-G {
    width: 100%;
    height: 720px;
    background: url("../../static/img/8.png") no-repeat center;
    background-size: cover;
  }
 .between-G .G-text {
  width: 100%;
  height: 359px;
  /* border: 1px solid red; */
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin:0 auto;
}
.between-G .G-text p:nth-of-type(1) {
  width: 100%;
  height: 32px;
  text-align: center;
  font-size: 20px;
  font-family: PingFang SC;
  margin-top: -70px;
  line-height: 32px;
  /* border: 1px solid burlywood; */
  color: rgba(255, 255, 255, 1);
}
.between-G .G-text p:nth-of-type(2) {
  width: 400px;
  height: 65px;
  font-size: 14px;
  font-family: PingFang SC;
 
  line-height: 36px;
  text-align: center;
  text-indent: 2em;
  color: rgba(255, 255, 255, 1);
  /* border: 1px solid blue; */
  margin-top: 10px;
}
.between-G .G-text button {
  width:80px;
  height: 30px;
  background: rgba(44, 113, 218, 1);
  box-shadow: 0px 15px 20px rgba(0, 0, 0, 0.1);
  opacity: 1;
  border-radius: 40px;
  margin-top: 35px;
  letter-spacing: 1px;
  font-size: 12px;
  line-height: 30px;
  text-align: center;
  
  font-family: PingFang SC;
  
  
  color: rgba(255, 255, 255, 1);
}
}
.G-text {
  width: 1159px;
  height: 359px;
  /* border: 1px solid red; */
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin: 0 auto;
}
.G-text p:nth-of-type(1) {
  width: 1159px;
  height: 96px;
  text-align: center;
  font-size: 60px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 72px;
  /* border: 1px solid burlywood; */
  color: rgba(255, 255, 255, 1);
}
.G-text p:nth-of-type(2) {
  width: 650px;
  height: 96px;
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 600;
  line-height: 36px;
  text-align: center;
  text-indent: 2em;
  color: rgba(255, 255, 255, 1);
  /* border: 1px solid blue; */
  margin-top: 20px;
}
.G-text button {
  width: 240px;
  height: 60px;
  background: rgba(44, 113, 218, 1);
  box-shadow: 0px 15px 20px rgba(0, 0, 0, 0.1);
  opacity: 1;
  border-radius: 40px;
  margin-top: 20px;
  letter-spacing: 5px;
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 500;
  line-height: 36px;
  color: rgba(255, 255, 255, 1);
}
.between-H {
  width: 100%;
  height: 394px;
  background: #3c3d41;
  display: flex;
  position: relative;
  /* border: 1px solid blue; */
  justify-content: center;
  border: 1px dashed #888888;
  border-top: transparent;
}
@media screen and (max-width: 420px) {
 .between-H{
   height: 250px;
 }
 .between-H .H-left {
  /* border: 1px solid red; */
  position: absolute;
  left: 350px;
  top: 70px;
  display: none;
}
.between-H .H-right {
  /* border: 1px solid red; */
  position: absolute;
  right: 350px;
  top: 70px;
  display: none;
}
}
.H-right {
  /* border: 1px solid red; */
  position: absolute;
  right: 350px;
  top: 70px;
}
.H-left {
  /* border: 1px solid red; */
  position: absolute;
  left: 350px;
  top: 70px;
}
.H-textA,
.H-textB,
.H-textC {
  width: 120px;
  height: 120px;
  /* border: 1px solid red; */
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  align-items: center;
  font-size: 12px;
  margin-top: 65px;
  margin-left: 20px;
}
.H-textA p {
  /* border: 1px solid blue; */
  height: 16px;
  width: 63px;
  font-family: Montserrat;
  font-weight: bold;
  margin: 5px 0;
  color: rgba(255, 255, 255, 1);
}
.H-textB p {
  /* border: 1px solid blue; */
  height: 16px;
  width: 63px;
  font-family: Montserrat;
  font-weight: bold;
  margin: 5px 0;
  color: rgba(255, 255, 255, 1);
}
.H-textC p {
  /* border: 1px solid blue; */
  font-size: 13px;
  font-family: Montserrat;
  font-weight: 400;
  line-height: 18px;
  color: rgba(255, 255, 255, 1);
  opacity: 0.5;
  height: 18px;
  width: 91px;
  margin: 5px 0;
}
.content-C .show {
  height: 240px;
  width: 240px;
  background: rgba(17, 19, 36, 0.8);
  /* border: 2px solid red; */
  box-shadow: 0px 0px 30px rgba(25, 26, 41, 0.5);
  position: absolute;
  left: 135px;
  top: 127px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.content-C .show p:nth-of-type(1) {
  width: 179px;
  height: 40px;
  font-size: 14px;
  font-family: Montserrat;
  font-weight: bold;
  margin-top: 20px;
  color: rgba(255, 255, 255, 1);
  opacity: 1;
}
.content-C .show p:nth-of-type(2) {
  width: 179px;
  height: 111px;
  font-size: 16px;
  font-family: PingFang SC;
  font-weight: 400;
  line-height: 24px;
  color: rgba(255, 255, 255, 0.8);
  opacity: 1;
}
</style>

