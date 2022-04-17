<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light px-4 border-bottom">
      <div class="container-fluid px-0 py-4 d-flex justify-content-between">
        <router-link class="navbar-brand text-center text-uppercase fs-3 mp-0" to="#">
          <span class="text-fade-black-1">baltic</span>arch.
        </router-link>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
          <ul class="navbar-nav text-uppercase">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center active" aria-current="page" to="#">home</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">pages</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">elements</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">blog</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">portofolio</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">shop</router-link>
            </li>
          </ul>
        </div>

        <div class="d-flex justify-content-center align-items-center d-none d-lg-block">
          <router-link class="text-decoration-none mx-3" to="#"><i class="fas fa-search"></i></router-link>
          <router-link class="text-decoration-none mx-3" to="#">RU</router-link>
          <router-link class="text-decoration-none mx-3" to="#">LV</router-link>
          <router-link class="text-decoration-none mx-3 active" to="#">EN</router-link>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

