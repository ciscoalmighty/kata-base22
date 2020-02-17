<template>
  <div class="container" id="footer">
    <b-navbar toggleable="lg" type="dark" variant="important">
      <b-navbar-brand href="/"
        ><img
          alt="Vue logo"
          src="../assets/logo.png"
        />AdoptMe.Org</b-navbar-brand
      >
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto" id="navlink">
          <b-nav-item href="/about" active>WHAT we do</b-nav-item>
          <b-nav-item href="/about" active>WHO we are</b-nav-item>
          <b-nav-item href="/about" active>EVENTS adoption</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <div class="row" id="address">
      <p>Main St #1245</p>
    </div>
    <div class="row" id="address">
      <p>
        Amazing City, 45677
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#footer {
  background: blue;
  position: relative;
  text-align: center;
  color: white;
  padding: 0.5rem 3rem;
  margin-top: 25px;
}
#address {
  padding: 0rem 3rem;
  color: white;
}

#navlink {
}
</style>
