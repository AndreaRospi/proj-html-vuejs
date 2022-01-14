<template>
  <div class="container">
    <div class="box-img">
      <img src="../../assets/img/counters-bg-image.jpg" alt="grafico-sfondo" />
      <div class="box-text">
        <p>Investment Numbers</p>
        <h1>Making An Impact In Our Communities</h1>
        <div class="button">learn more</div>
      </div>
    </div>
    <div class="box-num">
      <div class="square-num">
        <div class="num">86%</div>
        <div>Successful Applications</div>
      </div>
      <div class="square-num">
        <div class="num">94%</div>
        <div>Return On Investment</div>
      </div>
      <div class="square-num">
        <div class="num">92%</div>
        <div>Applied Solutions</div>
      </div>
      <div class="square-num">
        <div class="num">100%</div>
        <div>Completely Secure</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Investment",
};
</script>

<style lang="scss" scoped >
@import "../../assets/style/global.scss";
.container {
  display: flex;
  height: 360px;

  .box-img {
    position: relative;
    width: 45%;
    img {
      width: 100%;
      height: 100%;
    }
  }
  .box-text {
    width: 100%;
    position: absolute;
    top: 30%;
    left: 5%;
    color: white;
    h1 {
      font-weight: 300;
      margin: 15px 0px;
    }
    .button {
      display: inline-block;
    }
  }
  .box-num {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    width: 100%;
    .square-num {
      text-align: center;
      width: 50%;
      .num {
        font-size: 50px;
        color: #4a75b2;
      }
      div {
        color: #808080;
        font-size: 13px;
      }
    }
  }
}
</style>