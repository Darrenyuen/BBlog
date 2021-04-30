<template>
  <div id="header">
    <a href="/" class="logo-link">
      <img src="./../assets/logo.jpg">
    </a>
    <ul class="nav-list">
        <li class="nav-list-item">
          <a href="/" target="_self" class="nav-list-link active">BLOG</a>
        </li>
        <li class="nav-list-item">
          <a href="/archives" target="_self" class="nav-list-link active">ARCHIVE</a>
        </li>
        <li class="nav-list-item">
          <a href="https://github.com/darrenyuen" target="_blank" class="nav-list-link active">GITHUB</a>
        </li>
        <li class="nav-list-item">
          <a href="/about" target="_self" class="nav-list-link active">ABOUT</a>
        </li>
    </ul>
  </div>
</template>

<script>

export default {
  
  components: {

  }
}
</script>

<style>
#header {
  padding: 20px 10px;
  height: 60px;
  display: block;
  border-bottom: 1px solid #ddd;
}

img {
  float: left;
  height: 60px;
}

.nav-list {
  display: block;
  float: right;
  left: 80px;
  text-align: center;
  list-style-type: none;
  margin: auto;
}

.nav-list-item {
  display: inline-block;
  padding: 19px 10px;
  height: fit-content;
}

a, a:active {
  color: #2c3e50;
  text-decoration: none;
}
</style>
