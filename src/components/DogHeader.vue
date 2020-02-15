<template>
    <div class="container">
     <img src="../assets/dogs.jpg" style="width:100% height:200px padding: 0 0 0 0" />
        <div class= "bottom-left">This is your new family!</div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss">
#app {
  font-family:'Open Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.container {
  position: relative;
  text-align: center;
  color: white;
  padding-right: 0px;
  padding-left: 0px;
  height: 200px;
}

.bottom-left {
  position: absolute;
  bottom: 8px;
  left: 16px;
  opacity: 0.5;
  
}
#nav {
  padding: 0px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>