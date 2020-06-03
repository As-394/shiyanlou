<template>
  <div>
    <div class="daohang">
      <div class="daohang1">
        <img src="../../assets/123.jpg" alt class="tp" />
        <div class="dv">做实验，学编程</div>
        <div class="dv1 hover">企业版</div>
        <div class="dv2">|</div>
        <div class="dv3 hover">学校版</div>
        <div class="dv4 hover">登录</div>
        <div class="dv5 hover">注册</div>
      </div>
    </div>
    <div class="qb">
      <div class="kc">
        <img src="../../assets/11.jpg" alt class="tp1" />
        <div class="wz">全部课程</div>
        <div class="lz">
          <div class="dd hover">路径</div>
          <div class="dd1 hover">训练营</div>
          <div class="dd2 hover">楼+</div>
          <div class="dd3 hover">
            会员
            <img src="../../assets/64.png" alt class="hot" />
          </div>
          <div class="dd4 hover">
            社区▼
            <div class="dd4-1">
              <a href="https://www.shiyanlou.com/questions/" class="hover">讨论</a>
              <a href="https://www.shiyanlou.com/library/" class="hover">教程库</a>
              <a href="https://www.shiyanlou.com/live/" class="hover">直播</a>
              <a href="https://www.shiyanlou.com/contests/" class="hover">比赛</a>
            </div>
          </div>
          <div class="dd5">
            <input type="text" placeholder="搜索  课程/问答" />
            <img src="../../assets/32.png" alt class="tp3" />
          </div>
        </div>
      </div>
      <div class="lb"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
  props: {},
  components: {},
  data() {
    return {};
  },
  methods: {},
  mounted() {},
  watch: {},
  computed: {}
};
</script>

<style scoped lang='scss'>
.daohang {
  border: 1px solid red;
  width: 1520px;
  height: 120px;
  background-color: rgb(249, 249, 249);
}
.tp {
  margin-left: 170px;
  margin-top: 20px;
  position: absolute;
}
.dv {
  margin-left: 340px;
  margin-top: 46px;
  position: absolute;
  font-size: 21px;
}
.dv1 {
  position: absolute;
  margin-left: 1100px;
  margin-top: 50px;
  color: rgb(153, 165, 192);
  font-size: 18px;
}

.dv2 {
  position: absolute;
  margin-left: 1160px;
  margin-top: 50px;
  color: rgb(153, 165, 192);
  font-size: 18px;
}
.dv3 {
  position: absolute;
  margin-left: 1171px;
  margin-top: 50px;
  color: rgb(153, 165, 192);
  font-size: 18px;
}
.dv4 {
  position: absolute;
  margin-left: 1251px;
  margin-top: 50px;
  color: rgb(5, 118, 89);
  font-size: 17px;
}
.dv5 {
  position: absolute;
  margin-left: 1310px;
  margin-top: 37px;
  color: white;
  font-size: 17px;
  background-color: rgb(8, 191, 145);
  width: 80px;
  height: 50px;
  text-align: center;
  line-height: 50px;
}

.dv7 {
  color: rgb(153, 165, 192);
}
.qb {
  border: 1px solid red;
  width: 1520px;
  height: 70px;
}
.tp1 {
  position: absolute;
  margin-top: 15px;
}
.wz {
  position: absolute;
  margin-left: 40px;
  margin-top: 22px;
  color: white;
}
.kc {
  background-color: rgb(8, 191, 145);
  width: 200px;
  height: 70px;
  margin-left: 170px;
}
.dd {
  position: absolute;
  margin-left: 220px;
  margin-top: 20px;
}

.dd1 {
  position: absolute;
  margin-left: 280px;
  margin-top: 20px;
}
.dd2 {
  position: absolute;
  margin-left: 380px;
  margin-top: 20px;
}

.dd3 {
  position: absolute;
  margin-left: 450px;
  margin-top: 20px;
}

.dd4 {
  position: absolute;
  margin-left: 520px;
  margin-top: 5px;
  color: black;
  padding: 16px;
  font-size: 16px;

  cursor: pointer;
  display: inline-block;
}
.dd4 a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dd5 {
  position: absolute;
  margin-left: 900px;
  margin-top: 20px;
}
.tp3 {
  position: absolute;
  width: 15px;
  height: 15px;
  margin-left: 10px;
  margin-top: 5px;
}
.dd4-1 {
  margin-top: 15px;
  position: absolute;
  background-color: #f9f9f9;
  width: 100px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  padding: 12px 16px;
  margin-left: -30px;
  display: none;
}

.dd4:hover .dd4-1 {
  display: block;
}

.hover:hover {
  color: green;
  cursor: pointer;
}
.lb {
  border: 1px solid red;
  width: 1520px;
  height: 500px;
  background-color: red;
}
.hot {
  position: relative;
  width: 20px;
  height: 20px;
  bottom: 5px;
}
</style> 