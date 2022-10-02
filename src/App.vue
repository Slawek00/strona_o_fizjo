<template>
  <div>
      <AppBanner/>
      <AppMenu/>
      <AppContent/>
      <AppComponentCarrier/>
      <AppMethods/>
      <AppAboutPage/>
      <AppAboutVue/>
      <AppListImage/>
      <AppAboutBootstrap/>
      <AppFooter/>
  </div>
</template>

<script>
import AppBanner from "@/components/AppBanner.vue";
import AppMenu from  "@/components/AppMenu.vue";
import AppContent from "@/components/AppContent.vue";
import AppFooter from "@/components/AppFooter.vue";
import AppComponentCarrier from "@/components/AppComponentCarrier.vue";
import AppMethods from "@/components/AppMethods.vue";
import AppAboutPage from "@/components/AppAboutPage.vue";
import AppAboutVue from "@/components/AppAboutVue.vue";
import AppListImage from "@/components/AppListImage.vue";
import AppAboutBootstrap from "@/components/AppAboutBootstrap.vue";
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap/dist/js/bootstrap";

export default {
  name: 'App',
  components: {
    AppBanner,
    AppMenu,
    AppContent,
    AppComponentCarrier,
    AppMethods,
    AppAboutPage,
    AppAboutVue,
    AppListImage,
    AppAboutBootstrap,
    AppFooter
  }
}

</script>

<style>

</style>
