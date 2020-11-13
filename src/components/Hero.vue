<template>
  <div class="hero">
    <div class="container">
      <!-- Desktop -->
      <div class="d-none d-md-block">
        <div class="row mt-4">
          <div class="col-md-6">
            <div class="d-flex h-100">
              <div class="justify-content-center align-self-center">
                <h2>
                  <strong>Delicious Food Menu, </strong> <br />in Your Gadget
                </h2>
                <p>Ayo segera pilih dan pesan makanan Anda</p>
                <router-link class="btn btn-lg btn-success" to="/foods"
                  ><b-icon-arrow-right></b-icon-arrow-right> Pesan</router-link
                >
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <img src="../assets/images/hero.png" alt="Hero" width="100%" />
          </div>
        </div>
      </div>
    </div>

    <!-- Mobile -->
    <div class="d-md-none d-sm-block">
      <div class="row mt-4">
        <div class="col-md-6 mb-3">
          <img src="../assets/images/hero.png" alt="Hero" width="100%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Delicious Food Menu, </strong> <br />in Your Gadget
              </h2>
              <p>Ayo segera pilih dan pesan makanan Anda</p>
              <router-link class="btn btn-lg btn-success" to="/foods"
                ><b-icon-arrow-right></b-icon-arrow-right> Pesan</router-link
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
</style>