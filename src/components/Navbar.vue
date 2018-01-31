<template>
  <header class="header">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <b-navbar toggleable="md" type="dark">

            <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

            <b-navbar-brand href="/">VueDemo</b-navbar-brand>

            <b-collapse is-nav id="nav_collapse">

              <b-navbar-nav>
                <b-nav-item href="/">Home</b-nav-item>
                <b-nav-item href="/about">About</b-nav-item>
              </b-navbar-nav>

            </b-collapse>
          </b-navbar>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .navbar {
    padding: 15px 0 15px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.6);
  }
  .navbar a {
    color: white;
  }
  .navbar-dark .navbar-toggler,
  .navbar-dark .navbar-toggler:hover,
  .navbar-dark .navbar-toggler:focus,
  .navbar-dark .navbar-toggler:active {
    border: 0;
    cursor: pointer;
    padding: 0;
  }

  .navbar-dark .navbar-toggler:focus {
    outline: 0 dotted;
    outline: 0 auto -webkit-focus-ring-color;
  }
</style>
