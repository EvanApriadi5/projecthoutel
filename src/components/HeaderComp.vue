<template>
  <div id="HeaderComp">
    <nav class="navbar navbar-expand-lg navbar-light bg-header">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="../assets/logo.png" alt=""
        />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div
          class="collapse navbar-collapse justify-content-end"
          id="navbarNavAltMarkup"
        >
          <div class="navbar-nav">
            <a class="nav-link active" aria-current="page" href="#">Beranda</a>
            <a class="nav-link" href="#">Tentang Kami</a>
            <a class="nav-link" href="#">Tipe Kamar</a>
            <a href="#" class="btn btn-primary">Hubungi Kami</a>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "HeaderComp",
};
</script>

<style>
</style>