<template>
  <main>
    <Jumbo />
    <Client />
  </main>
</template>

<script>
import Jumbo from "../elements/Jumbo.vue";
import Client from "../elements/Client.vue";

export default {
  name: "main",
  components: {
    Jumbo,
    Client,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
</style>