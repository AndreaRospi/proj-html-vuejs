<template>
  <main>
    <Jumbo />
    <Client />
    <Cloud />
    <SpecialtyServices />
    <Investment />
  </main>
</template>

<script>
import Jumbo from "../elements/Jumbo.vue";
import Client from "../elements/Client.vue";
import Cloud from "../elements/Cloud.vue";
import SpecialtyServices from "../elements/SpecialtyServices.vue";
import Investment from "../elements/Investment.vue";

export default {
  name: "main",
  components: {
    Jumbo,
    Client,
    Cloud,
    SpecialtyServices,
    Investment,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
</style>