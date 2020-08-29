<template>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-xl-8">
        <div class="card card-profile shadow">
          <div class="row justify-content-center">
            <div class="col-lg-3 order-lg-2">
              <div class="card-profile-image"><a href="#"><img src="/img/team-4-800x800.jpg" class="rounded-circle"></a>
              </div>
            </div>
          </div>
          <div class="card-header text-center border-0 pt-4 pb-4">
            <div class="d-flex justify-content-between">
              <button class="btn btn-primary">B1</button>
              <button class="btn btn-warning">B2</button>
            </div>
          </div>
          <div class="card-body pt-0 pt-md-4">
            <div class="row">
              <div class="col">
                <div class="card-profile-stats d-flex justify-content-center mt-3">
                  <div><span class="heading">22</span><span class="description">Friends</span></div>
                  <div><span class="heading">10</span><span class="description">Photos</span></div>
                  <div><span class="heading">89</span><span class="description">Comments</span></div>
                </div>
              </div>
            </div>
            <div class="text-center"><h3> Jessica Jones<span class="font-weight-light">, 27</span></h3>
              <div class="h5 font-weight-300"><i class="ni location_pin mr-2"></i>Bucharest, Romania</div>
              <div class="h5 mt-4"><i class="ni business_briefcase-24 mr-2"></i>Mock up
              </div>
              <div><i class="ni education_hat mr-2"></i>University of Computer Science</div>
              <hr class="my-4">
              <p>Ryan — the name taken by Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and records
                all of his own music.</p><a href="#">Show more</a></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Profile',
    props: {
      msg: String
    }
  }
</script>

<style>
</style>
