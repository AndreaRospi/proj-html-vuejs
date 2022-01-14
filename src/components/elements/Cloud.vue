<template>
  <div class="container">
    <div class="box">
      <h1>Cloud Based Finance</h1>
      <hr />
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur
        laudantium suscipit eveniet, accusantium voluptatum reprehenderit,
      </p>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur
        laudantium suscipit eveniet, accusantium voluptatum reprehenderit,
      </p>
      <div class="button">learn more</div>
    </div>
    <div class="box">
      <img src="../../assets/img/graph.jpg" alt="grafico" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Cloud",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
.container {
  width: 80%;
  margin: 150px auto;
  display: flex;
  align-items: center;
  .box {
    width: 50%;
    margin-right: 30px;
    h1 {
      font-size: 50px;
      font-weight: 400;
    }
    hr {
      border: 1px solid #1a3154;
      width: 10%;
      margin: 25px 0;
    }
    p {
      margin-top: 25px;
    }
    .button {
      display: inline-block;
      margin-top: 40px;
    }
    img {
      width: 100%;
    }
  }
}
</style>