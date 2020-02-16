<template>
  <div class="container" id="dogpics">
    <div class="row">
      <div class="col-sm-12"></div>
    </div>
    <div class="row" id="botrow"></div>
    <div class="bottom-left">
      <h1>This is your new Family!</h1>
      <br />
      <button id="adoptbutton">Adopt Now</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.container {
  position: relative;
  text-align: center;
  color: #f50d11;
  padding-right: 0px;
  padding-left: 0px;
  height: 350px;
  object-fit: scale-down;
}
#botrow {
  position: relative;
  text-align: center;
  color: f50d11;
  font-weight: bold;
  height: 150px;
}
#adoptbutton {
  position: relative;
  text-align: left;
  color: #f50d11;
  background-color: transparent;
  border: 2px solid #f50d11;
  font-weight: bold;
}
#dogpics {
  background-image: url("../assets/dogs.jpg");
  height: 500px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.bottom-left {
  position: absolute;
  bottom: 8px;
  left: 16px;
  opacity: 0.5;
}
</style>
