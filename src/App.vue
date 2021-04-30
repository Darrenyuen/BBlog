<template>
  <div id="app">
    <Header/>
    <article-list> </article-list>
    <Footer></Footer>
  </div>
</template>

<script>

  import Header from "./components/Header.vue";
  import ArticleList from "./components/ArticleList.vue";
  import Footer from "./components/Footer.vue";

export default {
  name: 'App',
  components: {
    Header,
    ArticleList,
    Footer
  }
}
</script>

<style>
#app {
  width: 1050px;
  margin: 0 auto;
}
</style>
