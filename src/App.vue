<template>
  <HeaderComponent />
  <main class="my-5 py-5">
    <router-view />
  </main>
  <FooterComponent />
</template>

<script>
import $ from 'jquery';
import HeaderComponent from "@/components/HeaderComponent.vue"
import FooterComponent from "@/components/FooterComponent.vue"

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent
  },
  mounted: function() {
    document.addEventListener("DOMContentLoaded", function() {
      function mobileViewUpdate() {
        var viewportWidth = $(window).width();
        if(viewportWidth < 600) {
          $('.navbar.fixed-top').addClass('scrolled');
          $('.navbar-brand').addClass('scrolled');
        } else {
          $(document).scroll(function() {
            var $nav = $(".navbar.fixed-top");
            var $brand = $(".navbar-brand");
            $nav.toggleClass('scrolled', $(this).scrollTop() > $nav.height());
            $brand.toggleClass('scrolled', $(this).scrollTop() > $nav.height());
          });
        }
      }

      $(window).on("load", mobileViewUpdate);
      $(window).on("resize", mobileViewUpdate);

      mobileViewUpdate();
    });
  }
}
</script>

<style>
/* Style Here */
</style>
