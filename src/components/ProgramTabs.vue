<template>
  <div class="container" id="program">
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
          <div class="row" id="cards">
            <div class="col-sm-8">
              <div class="card">
                <div class="card-horizontal">
                  <div class="img-square-wrapper">
                    <img
                      id="programdogpics"
                      src="../assets/friend-in-trouble.png"
                      alt="Card image cap"
                    />
                  </div>
                  <div class="card-body">
                    <h3 class="card-title" id="titles">BEHAVIOR PROGRAM</h3>
                    <p class="card-text">
                      Evalution of each dog using specialists who determine the
                      best training that will help your friend be a better
                      family member.
                    </p>
                    <button id="learnbutton">Learn More</button>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-sm-4" >
              <img src="../assets/cutedog.jpg" id="programdogpics" />
            </div>
          </div>
          <div class="row" id="cards">
            <div class="col-sm-8">
              <div class="card">
                <div class="card-horizontal">
                  <div class="img-square-wrapper">
                    <img
                      id="programdogpics"
                      src="../assets/friend-in-trouble.png"
                      alt="Card image cap"
                    />
                  </div>
                  <div class="card-body">
                    <h3 class="card-title" id="titles">MY NEXT FAMILY</h3>
                    <p class="card-text">
                      Are you looking for a new family member? Then, this
                      program is for your. Dont buy, adopt here, and let's give
                      a home to this amazing friends.
                    </p>
                    <button id="learnbutton">Learn More</button>
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
        Food truck fixie locavore.
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
#program {
  margin-bottom: 25px;
}
#learnbutton {
  position: relative;
  text-align: left;
  color: red;
  background-color: transparent;
  border: 2px solid red;
  font-weight: bold;
}
#titles {
  color: red;
}
#cards {
  max-height: 200px;
}
#programdogpics {
  max-height: 350px;
  object-fit: scale-down;
  margin-bottom: 25px;
}
</style>
