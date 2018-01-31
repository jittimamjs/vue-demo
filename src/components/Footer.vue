<template>
  <footer class="footer">
    <div class="container text-center">
      <div class="col-lg-12">
        <small> Vue demo by Jittima<br>Copyright &copy; 2018</small>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: 'Footer'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    color: white;
  }
  footer>.container>.col-lg-12 {
    padding-bottom: 20px;
    padding-top: 20px;
    border-top: 1px solid rgba(255, 255, 255, 0.6);
  }
</style>
