<template>
  <footer class="border-top">
    <div class="container">
      <div class="row py-5">
        <div class="col-lg-6 mb-5 order-0 order-lg-0">
          <div class="wrapper">
            <div class="mb-5 mb-lg-0 text-center text-lg-start">
              <p class="mp-0">Subscribe to our newsletter to receive exclusive
                <br /> information about us and our services</p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 mb-5 order-2 order-lg-1">
          <div class="wrapper">
            <div class="mb-5 mb-lg-0">
              <ul class="d-flex flex-column flex-lg-row justify-content-between mp-0">
                <li class="d-inline">
                  <router-link class="nav-link text-center" to="#">Company</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link text-center" to="#">Objects</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link text-center" to="#">Services</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link text-center" to="#">Careers</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link text-center" to="#">Contacts</router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-lg-6 mb-5 order-0 order-lg-2">
          <div class="wrapper">
            <div class="mb-5 mb-lg-0 w-50 border-bottom-1px mx-auto mx-lg-0">
              <div class="d-flex align-items-center">
                <input class="form-control border-0" type="email" id="email">
                <i class="fas fa-arrow-right text-fade-black-1"></i>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mb-5 order-3 order-lg-3">
          <div class="wrapper">
            <div class="mb-5 mb-lg-0">
              <div class="d-flex align-items-center justify-content-center justify-content-lg-start">
                <router-link class="text-decoration-none mx-3" to="#"><i class="fab fa-twitter"></i></router-link>
                <router-link class="text-decoration-none mx-3" to="#"><i class="fab fa-facebook-f"></i></router-link>
                <router-link class="text-decoration-none mx-3" to="#"><i class="fab fa-instagram"></i></router-link>
                <router-link class="text-decoration-none mx-3" to="#"><i class="fab fa-linkedin-in"></i></router-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mb-5 order-4 order-lg-4">
          <div class="wrapper">
            <div class="mb-5 mb-lg-0 text-center text-lg-start">
              <p class="text-fade-black-1">&copy; <span class="text-black">Baltic Arch.</span> All Rights Reserved</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>