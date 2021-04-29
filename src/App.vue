<template>
  <div>
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

</style>
