<template>
  <nav class="nav-bar">
    <ul class="nav-bar__list">
      <li
        class="nav-bar__item"
        v-for="(item, index) in dataShared.navBar"
        :key="index"
      >
        <a :href="item.url">{{ item.name }}</a>
      </li>
    </ul>
  </nav>
</template>

<script>
import dataShared from "../../share/dataShare";
export default {
  name: "NavBar",
  data() {
    return {
      dataShared,
    };
  },
};
</script>

<style lang="scss" scoped>
.nav-bar {
  height: 100%;
  line-height: 90px;
  &__list {
    display: flex;
    list-style: none;
    align-items: center;
  }
  &__item:hover {
    background-color: #f6f7f7;
  }
  &__item {
    padding: 0 35px;

    a {
      text-transform: uppercase;
      text-decoration: none;
      color: #969595;
    }
    a:hover {
      color: #16304b;
    }
  }
}
</style>