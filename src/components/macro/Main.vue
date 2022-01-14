<template>
  <main>
    <Jumbo />
    <Client />
    <Cloud />
  </main>
</template>

<script>
import Jumbo from "../elements/Jumbo.vue";
import Client from "../elements/Client.vue";
import Cloud from "../elements/Cloud.vue";

export default {
  name: "main",
  components: {
    Jumbo,
    Client,
    Cloud,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
</style>