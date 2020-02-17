<template>
  <div class="container" id="volcontainer">
    <div class="row">
      <div class="col-sm-5">
        <div class="card" id="volcard" style="width:300px height=200">
          <div class="card-header" id="cardheader">Volunteers</div>
          <div class="card-body" id="cardbody">
            <img
              class="card-img-top"
              src="../assets/girl.png"
              alt="Card image"
              style="width:100%"
            />
          </div>
          <div class="card-footer" id="cardfooter">
            Amazing people, doing the difference every single day. Join us now
            of a community that is changing the world.
            <br />
            <button id="volbutton">Join Us</button>
          </div>
        </div>
      </div>
      <div class="col-sm-7" id="videobox">
        <div class="card" id="videocard">
          <div class="card-header" id="videoheader">
            Testimonial of the Month
          </div>
          <div class="card-body embed-responsive embed-responsive-16by9">
            <iframe
              width="560"
              height="315"
              src="https://www.youtube.com/embed/CQKGI0SbnFo?controls=0"
              frameborder="0"
              allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#volcontainer {
  height: 400px;
}
#cardheader {
  font-weight: bold;
  text-transform: uppercase;
  text-align: left;
  background-color: blue;
  color: azure;
}
.card-body {
  flex: 0 0 auto;
  padding: 0px 0px 0px 0px;
}
#cardbody {
  background-position: center;
  background-repeat: no-repeat;
  background-size: fill;
  position: relative;
  padding: 0 0 0 0;
  flex: 0 0 auto;
}
#cardfooter {
  text-align: left;
  color: gray;
  flex: 0 0 0 0;
}
#videoheader {
  font-weight: bold;
  text-transform: uppercase;
  text-align: left;
  background-color: red;
  color: azure;
}

#volcard {
  height: 400px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

#volbutton {
  position: relative;
  text-align: left;
  color: blue;
  background-color: transparent;
  border: 2px solid blue;
  font-weight: bold;
}
#videobox {
}
</style>
