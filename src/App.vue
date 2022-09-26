<template>
  <div>
    <AppBanner/>
    <AppMenu/>
    <AppContent/>
    <AppFooter/>
  </div>
</template>

<script>
import AppBanner from "@/components/AppBanner.vue";
import AppMenu from  "@/components/AppMenu.vue";
import AppContent from "@/components/AppContent.vue";
import AppFooter from "@/components/AppFooter.vue";
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap/dist/js/bootstrap";

export default {
  name: 'App',
  components: {
    AppBanner,
    AppMenu,
    AppContent,
    AppFooter
  }
}

</script>


<style>

</style>
