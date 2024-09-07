<template>
  <header>
    <ul>
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><nuxt-link to="/company">Company</nuxt-link></li>
      <li><nuxt-link to="/product">Product</nuxt-link></li>
      <li><nuxt-link to="/recruit">Recruit</nuxt-link></li>
    </ul>
  </header>
</template>

<style scoped>
  header ul {
    display: flex;
    margin: 0 0 .2em .2em;
    /* margin-left: .2em; */
    padding: 0;
    list-style-type: none;
  }
  header ul li {
    margin: 0;
    padding: .2em;
    margin-right: .6em;
  }
  header a {
    text-decoration: none;
  }
  header a.nuxt-link-exact-active {
    text-decoration: underline;
    background-color: gold;
  }
</style>