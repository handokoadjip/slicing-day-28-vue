<template>
  <section class="my-3 py-3">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 d-none d-lg-block">
          <div class="wrapper">
            <nav class="text">
              <router-link class="text-decoration-none d-block mb-3 active" to="#">About</router-link>
              <router-link class="text-decoration-none d-block mb-3" to="#">Policy</router-link>
              <router-link class="text-decoration-none d-block mb-3" to="#">Quality</router-link>
              <router-link class="text-decoration-none d-block mb-3" to="#">Responsibility
              </router-link>
              <router-link class="text-decoration-none d-block mb-3" to="#">Enterprises</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-8">
          <div class="wrapper">
            <p class="mb-4 pb-4">
              Founded in 2003 in Riga, Baltic Arch is a global architecture company that has grown to include 500
              employess working out of a combined 7 offices in the largest cities of Latvia.
            </p>
            <p class="mb-4 pb-4">
              From education and healthcare to mixed-use and transit-oriented devevlopments, we design for a
              sustainable and resilient future, and to enchance th human experience through the built environtemnt,
              providing all services required for the commissioning of objects.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "HistoryComponent",
}
</script>