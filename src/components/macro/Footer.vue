<template>
  <footer>
    <FooterTop />
  </footer>
</template>

<script>
import FooterTop from "../elements/FooterTop.vue";
export default {
  name: "Footer",
  components: {
    FooterTop,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
</style>