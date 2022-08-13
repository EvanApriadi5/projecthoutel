<template>
  <div id="PemesananComp">
    <div class="container">
      <div class="row justify-content-between mt-4">
        <!--  -->
        <div class="row">
          <div class="col-lg-5">
            <img src="../assets/amaris.png" alt="" class="img-detail" />
          </div>
          <div class="col-lg-4 mt-4">
            <h1><b>Amaris Hotel Palembang</b></h1>
            <p>Jalan Inspektur Marzuki - Kota Palembang</p>
            <div class="row">
              <div class="col mt-2">
                <img class="ic_star" src="../assets/Star1.png" />
                <img class="ic_star" src="../assets/Star1.png" />
                <img class="ic_star" src="../assets/Star1.png" />
                <img class="ic_star" src="../assets/Star1.png" />
                <span><B>4.5 Rb rate</B></span>
              </div>
            </div>
          </div>
        </div>

        <div class="row mt-5">
          <div class="col">
            <h3>Masukan Rincian Pemesanan</h3>
          </div>
        </div>
        <div class="row mt-5">
          <div class="col">
            <h4>Nama</h4>
          </div>
        </div>
        <div class="pencarian">
          <div class="row justify-content-start mt-2">
            <div class="col-lg-7 mt-3">
              <div class="input-group mb-3 shadow">
                <input
                  type="text"
                  class="form-control"
                  placeholder="input nama"
                  aria-describedby="basic-addon1"
                />
              </div>
            </div>
          </div>
        </div>

        <div class="row mt-5">
          <div class="col">
            <h4>Email</h4>
          </div>
        </div>
        <div class="pencarian">
          <div class="row justify-content-start mt-2">
            <div class="col-lg-7 mt-3">
              <div class="input-group mb-3 shadow">
                <input
                  type="text"
                  class="form-control"
                  placeholder="input email"
                  aria-describedby="basic-addon1"
                />
              </div>
            </div>
          </div>
        </div>

        
        <div class="row mt-5">
          <div class="col">
            <h4>Telepon</h4>
          </div>
        </div>
        <div class="pencarian">
          <div class="row justify-content-start mt-2">
            <div class="col-lg-7 mt-3">
              <div class="input-group mb-3 shadow">
                <input
                  type="text"
                  class="form-control"
                  placeholder="input Telepon"
                  aria-describedby="basic-addon1"
                />
              </div>
            </div>
          </div>
        </div>
        
        <div class="row">
            <div class="col-lg-5 mt-5">
                <h4>Pilih Metode Pembayaran</h4>
            </div>
            </div>
            <div class="row mt-5">
                <h5>Tipe Kamar</h5>
            </div>
            <div class="row">
            <div class="col-lg-3">
<div class="input-group mb-3 shadow">
  <select class="form-select" id="inputGroupSelect01">
    <option selected>Standar Double...</option>
    <option value="1">One</option>
    <option value="2">Two</option>
    <option value="3">Three</option>
  </select>
</div>
</div>
</div>

<div class="row mt-3">
  <h5>Metode Pembayaran</h5>
  <div class="col-lg-3">
<div class="input-group mb-3 shadow">
  <select class="form-select" id="inputGroupSelect01">
    <option selected>Virtual Account...</option>
    <option value="1">One</option>
    <option value="2">Two</option>
    <option value="3">Three</option>
  </select>
</div>
 </div>


<div class="col-lg-2 mb-3">
<img src="../assets/mandiri.png" width="100px" alt="" class="img-mandiri" />

</div>
<div class="col-lg-3 mb-3">
<p><b>Mandiri Virtual Account</b></p>
<p><b>90089181873817</b></p>
<p><b>a.n Houtel Indah</b></p>
</div>
</div>

<div class="row">
  <div class="col">
  <router-link to="/SuccesView" class="btn btn-primary">Proses Pembayaran</router-link>
  </div>
</div>

        
        


      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PemesananComp",
};
</script>

<style>
</style>