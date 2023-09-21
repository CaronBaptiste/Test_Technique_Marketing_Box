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
          <CardConnect></CardConnect>
          <CardWork></CardWork>
        </div>
      </div>
      <div>
        <LogoPartner></LogoPartner>
        <CardDemoBlue></CardDemoBlue>
        <FooterGrid></FooterGrid>
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
import CardConnect from "./components/CardConnect.vue";
import CardWork from "./components/CardWork.vue";
import LogoPartner from "./components/LogoPartner.vue";
import CardDemoBlue from "./components/CardDemoBlue.vue";
import FooterGrid from "./components/FooterGrid.vue";
export default {
  name: "App",

  components: {
    PreNavbarAirCall,
    NavbarAirCall,
    HomeHeader,
    LogoSlidder,
    ProductGrid,
    ServiceGrid,
    CardConnect,
    CardWork,
    LogoPartner,
    CardDemoBlue,
    FooterGrid
  },
};
</script>

<style  >
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

.navFixed{
  position: fixed;
  z-index: 10;
  min-width: 100%;
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
  max-width: 1224px;
  margin-top: 22vh;
  grid-area: 1 / 2 / 2 / 3;
}

</style>
