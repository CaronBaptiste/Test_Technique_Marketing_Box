<template>
  <section class="center" style="margin-bottom: 4em;">
    <div>
      <p class="center txtApprouved" style="margin-bottom: 2.5em">APPROUVÉ PAR PLUS DE 17 000 ENTREPRISES</p>
      <div class="parentLogoSlidder">
        <div class="div1 mb3">
          <div>
            <img
              width="120px"
              height="73px"
              src="https://a.storyblok.com/f/157376/120x73/d92e9ebb2b/saint-gobain.svg"
              alt
              loading="lazy"
            />
          </div>
        </div>
        <div class="div2 mb3">
          <div>
            <img
              width="120px"
              height="73px"
              src="https://a.storyblok.com/f/157376/120x73/7407b2db63/audika.svg"
              alt
              loading="lazy"
            />
          </div>
        </div>
        <div class="div3 mb3">
          <div>
            <img
              width="120px"
              height="73px"
              src="https://a.storyblok.com/f/157376/120x73/a8ec06d066/izi-by-edf.svg"
              alt
              loading="lazy"
            />
          </div>
        </div>
        <div class="div4 mb3">
          <div>
            <img
              width="120px"
              height="73px"
              src="https://a.storyblok.com/f/157376/120x73/b9bd25aa0f/qonto.svg"
              alt
              loading="lazy"
            />
          </div>
        </div>
        <div class="div5 mb3">
          <div>
            <img
              width="120px"
              height="73px"
              src="https://a.storyblok.com/f/157376/120x73/66d1b20ca8/ankorstore.svg"
              alt
              loading="lazy"
            />
          </div>
        </div>
        <div class="div6 mb3">
          <div>
            <img
              width="120px"
              height="73px"
              src="https://a.storyblok.com/f/157376/120x73/eff047c9c1/openclassrooms.svg"
              alt
              loading="lazy"
            />
          </div>
        </div>
        <div class="div7 mb3">
          <div>
            <img
              width="120px"
              height="73px"
              src="https://a.storyblok.com/f/157376/120x73/d1a58085c7/aircaraibes.svg"
              alt
              loading="lazy"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "LogoSlidder",
};
</script>

<style>
.center {
  display: flex;
  justify-content: center;
}
.paddingLR {
  padding-left: 1em;
  padding-right: 1em;
}

.parentLogoSlidder {
  display: grid;
  grid-template-columns: repeat(7, 1fr);
  grid-template-rows: 1fr;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}

.div1 {
  grid-area: 1 / 1 / 2 / 2;
}
.div2 {
  grid-area: 1 / 2 / 2 / 3;
}
.div3 {
  grid-area: 1 / 3 / 2 / 4;
}
.div4 {
  grid-area: 1 / 4 / 2 / 5;
}
.div5 {
  grid-area: 1 / 5 / 2 / 6;
}
.div6 {
  grid-area: 1 / 6 / 2 / 7;
}
.div7 {
  grid-area: 1 / 7 / 2 / 8;
}

.mb3 {
  margin-bottom: 1.5em;
  padding-left: 1.5em;
  padding-right: 1.5em;
}
.txtApprouved{
  font-size: 16px; 
  font-weight: bold; 
  font-weight: 600;
  color:   rgba(21, 26, 40, 0.5);
  text-align: center; 
  letter-spacing: 1px;
  box-sizing: border-box;
}
</style>
