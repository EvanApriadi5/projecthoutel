<template>
  <div id="FooterComp">
    <div class="containter">
      <!-- bagian banner hitam -->
      <div class="bg-banner">
        <div class="row justify-content-between tulisan">
          <!-- awal bagian Houtel -->
          <div class="col-lg-3 Houtel">
            <div class="row">
              <div class="col">
                <h1>Houtel</h1>
                <div class="row">
                  <div class="col">
                    <p>Platform booking hotel Online Indonesia</p>
                    <div class="row">
                      <div class="col">
                        <p>© copyright Houtel 2022</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Akhir bagian Houtel -->

          <!-- awak bagian sosmed -->
          <div class="col-lg-3 Sosmed">
            <div class="row">
              <div class="col">
                <h6>follow social media kami</h6>
                <div class="row">
                  <div class="col medsos">
                    <img class="facebook" src="../assets/facebook.png" alt="">
                    <img class="instagram" src="../assets/instagram.png" alt="">
                    <img class="twitter" src="../assets/twitter.png" alt="">
                    <img class="youtube" src="../assets/youtube.png" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- akhir bagian sosmed -->
        </div>
      </div>
      <!-- akhir bagian banner hitam -->
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<style>
#FooterComp .bg-banner {
  background-image: url("../assets/footer.png");
  margin-top: 150px;
  height: auto;
  width: 100%;
}
#FooterComp .Houtel {
  margin-left: 100px;
  padding-top: 30px;
}
#FooterComp .Sosmed {
  margin-left: 100px;
  padding-top: 70px;
}
</style>