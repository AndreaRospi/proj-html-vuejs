<template>
  <main>
    <Jumbo />
    <Client />
    <Cloud />
    <SpecialtyServices />
    <Investment />
    <ClientFeedback />
    <Talk />
  </main>
</template>

<script>
import Jumbo from "../elements/Jumbo.vue";
import Client from "../elements/Client.vue";
import Cloud from "../elements/Cloud.vue";
import SpecialtyServices from "../elements/SpecialtyServices.vue";
import Investment from "../elements/Investment.vue";
import ClientFeedback from "../elements/ClientFeedback.vue";
import Talk from "../elements/Talk.vue";

export default {
  name: "main",
  components: {
    Jumbo,
    Client,
    Cloud,
    SpecialtyServices,
    Investment,
    ClientFeedback,
    Talk,
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/global.scss";
</style>