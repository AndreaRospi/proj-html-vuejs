<template>
  <main>
    <Jumbo />
  </main>
</template>

<script>
import Jumbo from "../elements/Jumbo.vue";
export default {
  name: "main",
  components: {
    Jumbo,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
</style>