<template>
  <div class="container">
    <img src="../../assets/img/home_finance_slider_bg.jpg" alt="mappa mondo " />
    <h1>Right Peoples<span>.</span> Right Investments<span>.</span></h1>
  </div>
</template>

<script>
export default {
  name: "Jumbo",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
.container {
  position: relative;
  img {
    width: 100%;
  }
  h1 {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-weight: 300;
    font-size: 70px;
    span {
      color: #5ddecc;
    }
  }
}
</style>