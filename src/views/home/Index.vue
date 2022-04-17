<template>
  <TitleComponent />
  <HistoryComponent />
  <OverviewComponent />
  <Image1Component />
  <Content1Component />
  <Image2Component />
  <ServicesComponent />
  <Content2Component />
</template>

<script>
import TitleComponent from "@/components/TitleComponent.vue";
import HistoryComponent from "@/components/HistoryComponent.vue";
import OverviewComponent from "@/components/OverviewComponent.vue";
import Image1Component from "@/components/Image1Component.vue";
import Content1Component from "@/components/Content1Component.vue";
import Image2Component from "@/components/Image2Component.vue";
import ServicesComponent from "@/components/ServicesComponent.vue";
import Content2Component from "@/components/Content2Component.vue";

export default {
  name: "HomePage",
  components: {
    TitleComponent,
    HistoryComponent,
    OverviewComponent,
    Image1Component,
    Content1Component,
    Image2Component,
    ServicesComponent,
    Content2Component,
  },
  mounted() {
    document.title = "Baltic Arch | Company"
  }
}
</script>
