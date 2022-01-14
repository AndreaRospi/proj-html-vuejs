<template>
  <div class="container">
    <div>
      <img
        src="../../assets/img/finance_logo_footer.png"
        alt="logo finance footer"
      />
    </div>
    <nav class="post">
      <h2>recent posts</h2>
      <ul>
        <li v-for="(item, index) in dataShared.navBarPosts" :key="index">
          <i class="fas fa-chevron-right"></i>
          <a :href="item.url">{{ item.name }}</a>
        </li>
      </ul>
    </nav>
    <nav class="services">
      <h2>Services</h2>
      <ul>
        <li v-for="(item, index) in dataShared.navBarServices" :key="index">
          <i class="fas fa-chevron-right"></i>
          <a :href="item.url">{{ item.name }}</a>
        </li>
      </ul>
    </nav>
    <nav class="latest">
      <h2>latest</h2>
      <div><i class="fab fa-twitter"></i></div>
    </nav>
  </div>
</template>

<script>
import dataShared from "../../share/dataShare";
export default {
  name: "FooterTop",
  data() {
    return {
      dataShared,
    };
  },
};
</script>

<style lang="scss" scoped>
.container {
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  background-color: #1a1b21;
  img {
    cursor: pointer;
  }
  .post {
    h2 {
      color: white;
      font-size: 25px;
      text-transform: uppercase;
      margin-bottom: 15px;
    }
    ul {
      list-style: none;
      li {
        color: #787878;
        margin-top: 25px;
      }
      a {
        text-decoration: none;
        color: #787878;
        margin-left: 5px;
      }
    }
    li:hover {
      color: #04c5e8;
    }
    a:hover {
      color: #04c5e8;
    }
  }
  .services {
    h2 {
      color: white;
      font-size: 25px;
      text-transform: uppercase;
      margin-bottom: 15px;
    }
    ul {
      list-style: none;
      li {
        color: #787878;
        margin-top: 25px;
      }
      a {
        text-decoration: none;
        color: #787878;
        margin-left: 5px;
      }
    }
    li:hover {
      color: #04c5e8;
    }
    a:hover {
      color: #04c5e8;
    }
  }
  .latest {
    margin-bottom: 80px;
    h2 {
      color: white;
      font-size: 25px;
      text-transform: uppercase;
      margin-bottom: 15px;
    }
    div {
      font-size: 30px;
      color: #5aaeeb;
      cursor: pointer;
    }
  }
}
</style>