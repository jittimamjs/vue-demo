<template>
  <div class="about text-center">
    <br>
    <br>
    <br>
    <!--<h1 class="animated bounceIn">{{ msg }}</h1>-->
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to the Vue.js demo!'
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1 {
    color: #eaeaea;
  }
</style>
