<template>
  <div id="BannerComp">
    <div class="container">
      <div class="bg-banner mt-3">
        <div class="row">
          <div class="col-lg-4 mt-5 banner-konten">
            <h1>Nikmati Liburan Yang Diimpikan.</h1>
            <p>
              Booking Hotel Impian Anda Sekarang Lebih Mudah Booking Online
              Dengan Hotel
            </p>
              <div class="row mt-5">
                <div class="col">
                  <router-link to="/ListView" class="btn btn-primary me-3">booking sekarang</router-link>
                  <a href="">lihat detail </a>
                </div>
              </div>
          </div>
        </div>
      </div>
      <!-- menu pencarian -->
      <div class="pencarian">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="input-group mb-3 shadow">
              <span class="input-group-text" id="basic-addon1">
                <img class="ic_search" src="../assets/search.png">
                <img>
              </span>
              <input
                type="text"
                class="form-control"
                placeholder="Cari Hotel Impianmu"
                aria-describedby="basic-addon1"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BannerComp",
};
</script>

<style>
#BannerComp .bg-banner {
  background-image: url(/src/assets/banner.png);
  width: 100%;
  background-size: cover;
  height: 395px;
  border-radius: 20px;
}
</style>