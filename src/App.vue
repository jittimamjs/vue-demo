<template>
  <div id="app">
    <navbar></navbar>
    <div class="container main">
      <router-view/>
    </div>
    <footer1></footer1>
  </div>
</template>

<script>

import Navbar from './components/Navbar'
import Footer1 from './components/Footer'

export default {
  name: 'App',
  components: {
    Navbar, Footer1
  }
}
</script>

<style>
  body {
    background-image: linear-gradient(to top, #37ecba 0%, #72afd3 100%);
    color: #eaeaea;
  }
  html {
    position: relative;
    min-height: 100%;
  }

  .main {
    margin-bottom: 30px;
    margin-top: 30px;
  }
</style>
