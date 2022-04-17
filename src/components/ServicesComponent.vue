<template>
  <section class="my-3 py-3">
    <div class="container">
      <div class="row">
        <div class="offset-lg-3 col-lg-8">
          <div class="wrapper">
            <h2 class="fs-6 mb-3">Services we provide:</h2>
            <div class="row">
              <div class="col-lg-6">
                <nav class="text">
                  <router-link class="text-decoration-none text-fade-black-1 d-block mb-3" to="#">House-building</router-link>
                  <router-link class="text-decoration-none text-fade-black-1 d-block mb-3" to="#">Engineering structure</router-link>
                  <router-link class="text-decoration-none text-fade-black-1 d-block mb-3" to="#">Bridges and hydrotechnical
                    structures</router-link>
                </nav>
              </div>
              <div class="col-lg-6">
                <nav class="text">
                  <router-link class="text-decoration-none text-fade-black-1 d-block mb-3" to="#">Recontructions and
                    restoration</router-link>
                  <router-link class="text-decoration-none text-fade-black-1 d-block mb-3" to="#">Interior</router-link>
                  <router-link class="text-decoration-none text-fade-black-1 d-block mb-3" to="#">Designing</router-link>
                </nav>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "OverviewComponent",
}
</script>