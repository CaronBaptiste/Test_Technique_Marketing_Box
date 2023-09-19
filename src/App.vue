<template>
  <div id="app">
    <div class="navFixed">
      <PreNavbarAirCall></PreNavbarAirCall>
      <NavbarAirCall></NavbarAirCall>
    </div>
    <div class="parentBody">
      <div class="divBody">
      <HomeHeader></HomeHeader>
      <LogoSlidder></LogoSlidder>
      <ProductGrid></ProductGrid>
      <ServiceGrid></ServiceGrid>
      </div>
    </div>
  </div>
</template>

<script>

import PreNavbarAirCall from "./view/PreNavbarAirCall.vue";
import NavbarAirCall from "./view/NavbarAirCall.vue";
import HomeHeader from "./components/HomeHeader.vue";
import LogoSlidder from "./components/LogoSlidder.vue";
import ProductGrid from "./components/ProductGrid.vue";
import ServiceGrid from "./components/ServiceGrid.vue";

export default {
  name: "App",

  components: {
    PreNavbarAirCall,
    NavbarAirCall,
    HomeHeader,
    LogoSlidder,
    ProductGrid,
    ServiceGrid,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

.navFixed{
  position: fixed;
  z-index: 10;
}

body {
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
}

.parentBody {
  display: grid;
  grid-template-columns: 1fr 2.5fr 1fr;
  grid-template-rows: 1fr;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}

.divBody {
  grid-area: 1 / 2 / 2 / 3;
  margin-top: 22vh;
}

</style>
