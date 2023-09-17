<template>
  <div class="parentBody" id="app">
     <div class="divBody">
      <PreHeader></PreHeader>
      <HeaderList></HeaderList>
      <HomeHeader></HomeHeader>
      <LogoSlidder></LogoSlidder>
      <ProductGrid></ProductGrid>
      <ServiceGrid></ServiceGrid>
    </div>
  </div>
</template>

<script>
import PreHeader from "./components/PreHeader.vue";
import HeaderList from "./components/HeaderList.vue";
import HomeHeader from "./components/HomeHeader.vue";
import LogoSlidder from "./components/LogoSlidder.vue";
import ProductGrid from "./components/ProductGrid.vue";
import ServiceGrid from "./components/ServiceGrid.vue";

export default {
  name: "App",

  components: {
    PreHeader,
    HeaderList,
    HomeHeader,
    LogoSlidder,
    ProductGrid,
    ServiceGrid,
  },
};
</script>

<style>
body
{
  margin: 0;
  padding: 0;
}
.parentBody {
  display: grid;
  grid-template-columns: 1fr 4fr 1fr;
  grid-template-rows: 1fr;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}

.divBody {
  grid-area: 1 / 2 / 2 / 3;
}
</style>
