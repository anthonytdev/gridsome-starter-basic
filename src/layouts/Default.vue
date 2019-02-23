<template>
  <div class="wrapper">
    <Header-layout></layout-header>
    <Nav-layout></layout-nav>
    <slot/>
    <Footer-layout></layout-footer>
  </div>
</template>

<script>
import HeaderLayout from "~partials/Header.vue";
import NavLayout from "~partials/Nav.vue";
import FooterLayout from "~partials/Footer.vue";

export default {
  components: {
    HeaderLayout,
    NavLayout,
    FooterLayout
  }
}
</script>
