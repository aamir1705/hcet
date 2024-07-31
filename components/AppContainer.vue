<template>
  <div class="md:mx-40 mx-0">
    <HoverImage />
    <TopNavbar />
    <Navbar />
    <slot></slot>
    <Footer />
  </div>
</template>
<script>
import "~/assets/css/main.css";
import HoverImage from "./HoverImage.vue";
import TopNavbar from "./TopNavbar.vue";
export default {
  name: "AppContainer",
};
</script>
