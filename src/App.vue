<template>
  <header class="header d-flex">
    <h1 class="header__title">前端大秘寶</h1>
    <nav class="header__links">
      <ul class="d-flex">
        <li>首頁</li>
        <li>工具</li>
        <li>文章</li>
        <li>連結</li>
      </ul>
    </nav>
  </header>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
</template>

<style lang="scss">
@import "@/assets/all.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
}

// #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }

.header {
  background: var(--COLOR-MAIN);
  // position: fixed;
  width: 100%;
  padding: 1rem;
  &__title {
    margin: 0;
  }
}


</style>
