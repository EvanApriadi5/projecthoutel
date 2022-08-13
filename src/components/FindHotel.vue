<template>
  <div id="FindHotel">
    <div class="container">
      <div class="row justify-content-center text-center">
        <div class="col-lg-4 mt-5 ms-5">
          <h1>Temukan Hotel yang anda impikan.</h1>
        </div>
      </div>
      <!-- menu pencarian find hotel -->
      <div class="pencarian">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="input-group mb-3 shadow">
              <span class="input-group-text" id="basic-addon1">
                <img class="ic_search" src="../assets/search.png" />
                <img />
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
      <div class="row mt-5">
        <div class="col text-center">
          <div class="bgfind pt-3">
            <h4>Rekomendasi Hotel Top Palembang</h4>
          </div>
        </div>
      </div>
      <!-- akhir rekomendasi findhotel -->
      <!-- card -->
      <div class="row justify-content-between mt-4">
        <div class="col-lg-4">
          <div class="card" style="width: 100%">
            <img src="../assets/alts.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">The Alts Hotel</h5>
              <p class="card-text">Rp. 200.000- / malam</p>
              <div class="row">
                <div class="col">
                  <router-link to="/PemesananView" class="btn btn-primary">Booking Sekarang</router-link>
                </div>
                <div class="col-lg-4 text-end mt-2">
                  <img class="ic_star" src="../assets/Star1.png" />
                  <span><b>4.5 RB</b></span>
                </div>
              </div>
            </div>
          </div>
        </div>
 
        <div class="col-lg-4">
          <div class="card" style="width: 100%">
            <img src="../assets/amaris.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Arista Hotel Palembang</h5>
              <p class="card-text">Rp. 200.000- / malam</p>
              <div class="row">
                <div class="col">
                  <a href="#" class="btn btn-primary">Booking Sekarang</a>
                </div>
                <div class="col text-end mt-3">
                  <img class="ic_star" src="../assets/Star1.png" />
                  <span><b>4.5 RB</b></span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4">
          <div class="card" style="width: 100%">
            <img src="../assets/arista.png" class="card-img-top" alt="..." />
            <div class="card-body"> 
              <h5 class="card-title">Amaris Hotel Palembang</h5>
              <p class="card-text">Rp. 200.000- / malam</p>
              <div class="row">
                <div class="col">
                  <a href="#" class="btn btn-primary">Booking Sekarang</a>
                </div>
                <div class="col text-end mt-3">
                  <img class="ic_star" src="../assets/Star1.png" />
                  <span><b>4.5 RB</b></span>
                </div>
              </div>
            </div> 
          </div>
        </div>
      </div>
    <!-- Card hotel 2 -->
    <div class="row justify-content-between mt-4">
        <div class="col-lg-4">
          <div class="card" style="width: 100%" >
            <img src="../assets/alts.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">The Alts Hotel</h5>
              <p class="card-text">Rp. 200.000- / malam</p>
              <div class="row">
                <div class="col">
                  <a href="#" class="btn btn-primary">Booking Sekarang</a>
                </div>
                <div class="col-lg-4 text-end mt-2">
                  <img class="ic_star" src="../assets/Star1.png" />
                  <span><b>4.5 RB</b></span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4">
          <div class="card" style="width: 100%">
            <img src="../assets/amaris.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Arista Hotel Palembang</h5>
              <p class="card-text">Rp. 200.000- / malam</p>
              <div class="row">
                <div class="col">
                  <a href="#" class="btn btn-primary">Booking Sekarang</a>
                </div>
                <div class="col text-end mt-3">
                  <img class="ic_star" src="../assets/Star1.png" />
                  <span><b>4.5 RB</b></span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-lg-4">
          <div class="card" style="width: 100%">
            <img src="../assets/arista.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Amaris Hotel Palembang</h5>
              <p class="card-text">Rp. 200.000- / malam</p>
              <div class="row">
                <div class="col">
                  <a href="#" class="btn btn-primary">Booking Sekarang</a>
                </div>
                <div class="col text-end mt-3">
                  <img class="ic_star" src="../assets/Star1.png" />
                  <span><b>4.5 RB</b></span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>




    </div>
  </div>
</template>

<script>
export default {
  name: "FindHotel",
};
</script>

<style>
</style>