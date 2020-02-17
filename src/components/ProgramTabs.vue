<template>
  <div class="container">
    <ul class="nav nav-tabs" id="myTab" role="tablist">
      <li class="nav-item">
        <a
          class="nav-link active"
          id="home-tab"
          data-toggle="tab"
          href="#home"
          role="tab"
          aria-controls="home"
          aria-selected="true"
          >Programs</a
        >
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          id="profile-tab"
          data-toggle="tab"
          href="#profile"
          role="tab"
          aria-controls="profile"
          aria-selected="false"
          >Associated Companys</a
        >
      </li>
    </ul>
    <div class="tab-content" id="myTabContent">
      <div
        class="tab-pane fade show active"
        id="home"
        role="tabpanel"
        aria-labelledby="home-tab"
      >
        <div class="container-fluid">
          <div class="row">
            <div class="col-12 mt-3">
              <div class="card">
                <div class="card-horizontal">
                  <div class="img-square-wrapper">
                    <img
                      class=""
                      src="../assets/friend-in-trouble.png"
                      alt="Card image cap"
                    />
                  </div>
                  <div class="card-body">
                    <h3 class="card-title">BEHAVIOR PROGRAM</h3>
                    <p class="card-text">
                      Evalution of each dog using specialists who determine the
                      best training that will help your friend be a better
                      family member.
                    </p>
                    <button>Learn More</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="tab-pane fade"
        id="profile"
        role="tabpanel"
        aria-labelledby="profile-tab"
      >
        Food truck fixie locavore, accusamus mcsweeney's marfa nulla
        single-origin coffee squid. Exercitation +1 labore velit, blog sartorial
        PBR leggings next level wes anderson artisan four loko farm-to-table
        craft beer twee. Qui photo booth letterpress, commodo enim craft beer
        mlkshk aliquip jean shorts ullamco ad vinyl cillum PBR. Homo nostrud
        organic, assumenda labore aesthetic magna delectus mollit. Keytar
        helvetica VHS salvia yr, vero magna velit sapiente labore stumptown.
        Vegan fanny pack odio cillum wes anderson 8-bit, sustainable jean shorts
        beard ut DIY ethical culpa terry richardson biodiesel. Art party
        scenester stumptown, tumblr butcher vero sint qui sapiente accusamus
        tattooed echo park.
      </div>
    </div>
    <div class="container-fluid">
      <div class="row">
        <div class="col-12 mt-3">
          <div class="card">
            <div class="card-horizontal">
              <div class="img-square-wrapper">
                <img
                  class=""
                  src="../assets/friend-in-trouble.png"
                  alt="Card image cap"
                />
              </div>
              <div class="card-body">
                <h3 class="card-title">MY NEXT FAMILY</h3>
                <p class="card-text">
                  Are you looking for a new family member? Then, this program is
                  for your. Dont buy, adopt here, and let's give a home to this
                  amazing friends.
                </p>
                <button>Learn More</button>
              </div>
            </div>
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
.card-horizontal {
  display: flex;
  flex: 1 1 auto;
}
</style>
