<template>
  <div id="HotelRec2">
    <div class="container">
      <div class="row justify-content-between mt-5">
        <div class="col-lg-3"></div>
        <div class="col-lg-6 text-center">
          <h3>Rekomendasi Berdasarkan Kota</h3>
        </div>
        <div class="col-lg-3 text-end">
          <a href="">lihat semua</a>
        </div>
      </div>

      <!-- akhir rekomendassi hotel -->

      <!-- image Kota -->
      <div class="row mt-5">
        <div class="col-lg-3 mt-2">
          <div class="bg-image">
            <div class="row">
              <div class="col Kota">
                <h3><b>Kota Jakarta</b></h3>
                <h5>110+ akomodasi</h5>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mt-2">
          <div class="bg-image2">
            <div class="row">
              <div class="col Kota">
                <h3><b>Kota Palembang</b></h3>
                <h5>110+ akomodasi</h5>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mt-2">
          <div class="bg-image3">
            <div class="row">
              <div class="col Kota">
                <h3><b>Kota Yogya</b></h3>
                <h5>110+ akomodasi</h5>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mt-2">
          <div class="bg-image4">
            <div class="row">
              <div class="col Kota">
                <h3><b>Kota Denpasar</b></h3>
                <h5>110+ akomodasi</h5>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Akhir bagian Kota -->
    </div>
  </div>
</template>
<script>
export default {
  name: "HotelRec2",
};
</script>

<style>
#HotelRec2 .bg-image {
  background-image:url(../assets/jakarta.png);
  border-radius: 20px;
  background-size: cover;
  width: 100%;
  height: auto;
  color: white;
  padding-top: 270px;
  padding-left: 35px;
}

#HotelRec2 h3 {
  font-size: 20px;

}
#HotelRec2 h5 {
  font-size: 16px;
}

#HotelRec2 .bg-image2 {
  background-image: url(../assets/palembang.png);
  border-radius: 20px;
  background-size: cover;
  width: 100%;
  height: auto;
  color: white;
  padding-top: 270px;
  padding-left: 35px;
}

#HotelRec2 .bg-image3 {
  background-image: url(../assets/yogya.png);
  border-radius: 20px;
  background-size: cover;
  width: 100%;
  height: auto;
  color: white;
  padding-top: 270px;
  padding-left: 35px;
}

#HotelRec2 .bg-image4 {
  background-image: url(../assets/denpasar.png);
  border-radius: 20px;
  background-size: cover;
  width: 100%;
  height: auto;
  color: white;
  padding-top: 270px;
  padding-left: 35px;
}
</style>
