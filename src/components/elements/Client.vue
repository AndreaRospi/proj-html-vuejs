<template>
  <div class="container">
    <div class="box">
      <img
        src="../../assets/img/client-logo-3-200x87.png"
        alt="electricity logo"
      />
    </div>
    <div class="box">
      <img
        src="../../assets/img/client-logo-4-200x87.png"
        alt="electricity logo"
      />
    </div>
    <div class="box">
      <img
        src="../../assets/img/client-logo-1-1-200x87.png"
        alt="electricity logo"
      />
    </div>
    <div class="box">
      <img
        src="../../assets/img/client-logo-5-200x87.png"
        alt="electricity logo"
      />
    </div>
    <div class="box">
      <img
        src="../../assets/img/client-logo-6-200x87.png"
        alt="electricity logo"
      />
    </div>
    <div class="box">
      <img
        src="../../assets/img/client-logo-3-200x87.png"
        alt="electricity logo"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Client",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
.container {
  height: 150px;
  display: flex;
  justify-content: space-around;
  background-color: #f9f9f9;
  .box {
    display: flex;
    align-items: center;
    img {
      cursor: pointer;
      filter: invert(0.6);
    }
  }
}
</style>