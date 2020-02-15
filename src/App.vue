<template>
 <div class="container">
  <b-navbar toggleable="lg" type="dark" variant="danger">
    <b-navbar-brand href="/"><img alt="Vue logo" src="../src/assets/logo.png" />AdoptMe.Org</b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
       <b-nav-item href="/about" active>WHAT we do</b-nav-item>
       <b-nav-item href="/about" active>WHO we are</b-nav-item>
       <b-link to="/about" active>EVENTS adoption</b-link>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  <router-view/>
</div>

</template>

<style lang="scss">
#app {
  font-family:'Open Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 15px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
  .container {
  position: relative;
  text-align: center;
  color: white;
  padding-right: 0px;
  padding-left: 0px;
}
}
</style>
