<template>
  <div>
    <div class="box-up">
      <h1>Client Feedback</h1>
      <hr />
    </div>
    <div class="box-down">
      <div class="card">
        <img
          src="../../assets/img/client-logo-4-200x87.png"
          alt="logo event levate"
        />
        <p>
          "Avada Finance offers a fantastic service! It is so easy to use and
          the customer support is the best around. This payment option is my
          number one choice. I always recommendit."
        </p>
        <div class="author">
          <p>Andre Mendoza</p>
          <span>creative market</span>
        </div>
      </div>
      <div class="card">
        <img
          src="../../assets/img/client-logo-1-1-200x87.png"
          alt="logo event levate"
        />
        <p>
          "Avada Finance offers a fantastic service! It is so easy to use and
          the customer support is the best around. This payment option is my
          number one choice. I always recommendit."
        </p>
        <div class="author">
          <p>Andre Mendoza</p>
          <span>creative market</span>
        </div>
      </div>
      <div class="card">
        <img
          src="../../assets/img/client-logo-2-200x87.png"
          alt="logo event levate"
        />
        <p>
          "Avada Finance offers a fantastic service! It is so easy to use and
          the customer support is the best around. This payment option is my
          number one choice. I always recommendit."
        </p>
        <div class="author">
          <p>Andre Mendoza</p>
          <span>creative market</span>
        </div>
      </div>
      <div class="card">
        <img
          src="../../assets/img/client-logo-3-200x87.png"
          alt="logo event levate"
        />
        <p>
          "Avada Finance offers a fantastic service! It is so easy to use and
          the customer support is the best around. This payment option is my
          number one choice. I always recommendit."
        </p>
        <div class="author">
          <p>Andre Mendoza</p>
          <span>creative market</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ClientFeedback",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
.box-up {
  text-align: center;
  padding: 85px 0;
  background-color: #f9f9f9;
  h1 {
    font-weight: 300;
  }
  hr {
    border: 1px solid #223d65;
    width: 5%;
    margin: 20px auto;
  }
}
.box-down {
  display: flex;
  .card {
    min-height: 350px;
    text-align: center;
    border: 1px solid #ebebeb;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    padding: 0 30px;
    img {
      width: 70%;
    }
    p {
      color: #9aa2ac;
    }
    .author {
      width: 100%;
      border-top: 1px solid #ebebeb;
      padding-top: 15px;
      text-transform: uppercase;
      span {
        font-size: 13px;
        color: #969595;
      }
    }
  }
}
</style>