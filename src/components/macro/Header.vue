<template>
  <header>
    <div>
      <img
        src="../../assets/img/finance_logo_1x.png"
        alt="logo avada finance"
      />
    </div>
    <div class="navigation">
      <NavBar />
      <div class="button-big">contact</div>
      <a href="#">+</a>
    </div>
  </header>
</template>

<script>
import NavBar from "../elements/NavBar.vue";
export default {
  name: "Header",
  components: {
    NavBar,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
header {
  img {
    cursor: pointer;
  }
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 90px;
  width: 90%;
  margin: 0 auto;
  color: #969595;
  .navigation {
    display: flex;
    align-items: center;
    height: 90px;
    a {
      text-decoration: none;
      color: inherit;
    }
    a:hover {
      color: #16304b;
    }
  }
}
</style>