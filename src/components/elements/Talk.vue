<template>
  <div class="container">
    <div class="box-text">
      <h1>Ready to talk?</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim ipsam fuga
        molestias minima pariatur excepturi, veniam aliquam provident.
      </p>
      <div class="button">let's talk</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Talk",
};
</script>

<style lang="scss" scoped>
.container {
  background-image: url(../../assets/img/ready_to_talk_cta_bg.jpg);
  background-size: contain;
  min-height: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  .box-text {
    width: 50%;
    text-align: center;
    h1 {
      color: white;
      font-weight: 300;
      font-size: 50px;
    }
    p {
      margin: 30px 0;
      color: #9aa2ac;
    }
    .button {
      display: inline-block;
    }
  }
}
</style>