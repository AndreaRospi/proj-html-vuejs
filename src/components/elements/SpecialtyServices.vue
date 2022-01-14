<template>
  <div class="container">
    <div class="box">
      <h1>Specialty Services</h1>
      <hr />
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit aliquam
        unde debitis deserunt fugiat? Quam eligendi dolorum quaerat consequatur
        debitis at exercitationem aut quidem magni modi saepe, illo quo
        excepturi.
      </p>
    </div>
    <div class="box-card">
      <div class="card">
        <div class="card-text">
          <div class="icona"><i class="fas fa-globe"></i></div>
          <h3>Small Business Loans</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cumque
            sunt quod possimus, doloribus ratione, hic aut aspernatur et
          </p>
        </div>
        <div class="button-xl">Learn More</div>
      </div>
      <div class="card">
        <div class="card-text">
          <div class="icona"><i class="far fa-gem"></i></div>
          <h3>Credit Rating Advice</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cumque
            sunt quod possimus, doloribus ratione, hic aut aspernatur et
          </p>
        </div>
        <div class="button-xl">Learn More</div>
      </div>
      <div class="card">
        <div class="card-text">
          <div class="icona"><i class="fas fa-chart-line"></i></div>
          <h3>Fast Crowd Funding</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cumque
            sunt quod possimus, doloribus ratione, hic aut aspernatur et
          </p>
        </div>
        <div class="button-xl">Learn More</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SpecialtyServices",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
.container {
  background-color: #f9f9f9;
  .box {
    width: 60%;
    text-align: center;
    margin: 0 auto;
    h1 {
      padding-top: 100px;
      font-size: 50px;
      font-weight: 300;
    }
    hr {
      margin: 30px auto;
      border: 1px solid #1a3154;
      width: 10%;
    }
  }
  .box-card {
    display: flex;
    width: 80%;
    margin: 100px auto;
    .card {
      text-align: center;
      margin: 0 15px;
      width: calc(100% / 3);
      background-color: white;
      .card-text {
        padding: 20px;
        .icona {
          color: #4876b5;
          font-size: 55px;
        }
        h3 {
          font-size: 30px;
          font-weight: 300;
          margin-bottom: 20px;
        }
        p {
          color: #949494;
          font-size: 13px;
          line-height: 2;
        }
      }
    }
  }
}
</style>