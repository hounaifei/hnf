<template>
  <div class="home">
    <div class="header">
      <van-row>
        <van-col :span="12">
          <img
            src="/img/logo.png"
            style="width:100px; height:55px; margin-left:10px; margin-top:10px"
          />
        </van-col>
        <van-col :span="6"></van-col>
        <van-col :span="6"></van-col>
      </van-row>
      <div class="banner">
        <img src="/img/banner.jpg" alt style="width: 100%;height:150px;" />
      </div>
      <div class="app">
        <ul class="my_ul">
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>装修方案</p>
          </li>
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>效果图</p>
          </li>
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>设计师</p>
          </li>
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>装修工地</p>
          </li>
        </ul>
       <ul class="my_ul">
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>装修攻略</p>
          </li>
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>装修贷款</p>
          </li>
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>免费预约</p>
          </li>
          <li class="my_li">
            <img src="/img/icon_logo.png" alt />
            <p>十秒报价</p>
          </li> 
        </ul>
      </div>
    </div>
      <div class="all">
            <div class="all_head">
                <span class="all_span"></span>
                <span class="all_span2">全屋装修</span>
                <span class="all_span3">包设计 包木才 包水电 包施工</span>
            </div>
            <div class="all_banner">
                <img src="/img/img1.jpg" alt=""  style="width:100%; height:165px;" >
            </div>
      </div>
  </div>
</template>

<script>
</script>
<style lang="scss" scoped>
.home {
  width: 100%;
  background: #eaeaea;

  .header {
    width: 100%;
    height: 450px;
    background: #fff;
    .van-row {
      width: 100%;
      height: 70px;
    }
    .banner {
      width: 100%;
      height: 160px;
    }
    .app {
      width: 100%;
      height: 200px;
      // border: 1px solid #000;
      .my_ul {
        width: 100%;
        height: 50%;
        display: flex;
        justify-content: space-around;
        // border: 1px solid #000;
        .my_li {
          flex: 3;
          //flex-direction: column;
          align-items: center;
          // border: 1px solid #000;
          flex-direction: column;
          justify-content: center;
          align-items: center;
        }
        .my_li > img {
          width: 50px;
          height: 50px;
          // border: 1px solid #000;
          background: #39c894;
          border-radius: 50%;
          margin-left: 20px;
        
        }
        .my_li > p {
          font-size: 16px;
          text-align: center;
        }
      }
    }
  }
  .all{
    width: 100%;
    height: 550px;
    border: 1px solid #000;
    background: #fff;
    margin-top: 10px;
    .all_head{
      width: 100%;
      height: 80px;
      border:1px solid #000;
      display: flex;
      .all_span{
        display: block;
        width: 8px;
        height: 40px;
        background: #2bb281;
        margin-top: 20px;
      }
      .all_span2{
           display: block;
           font-size: 23px;
          margin-top: 26px;
          margin-left: 15px;
      }
      .all_span3{
           display: block;
           font-size: 16px;
           color: #999999;
          margin-top: 31px;
          margin-left: 15px;
      }
    }
    .all_banner{
      width: 100%;
      height: 165px;
    }
  }
}
</style>
