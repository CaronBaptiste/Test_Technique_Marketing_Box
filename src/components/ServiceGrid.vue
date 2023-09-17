<template>
  <section>
    <div
      class="marginLeft marginRight center paddingLR"
      style="flex-wrap: wrap"
    >
      <h2 style="margin-bottom: 64px">
        Créez de la valeur à partir de vos appels
      </h2>
      <div class="parent3">
        <div class="div31">
          <div>
            <div>
              <div style="margin-bottom: 24px">
                <img
                  style="width: 472px; height: 302px"
                  src="https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/"
                  srcset="
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/48x0   48w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/96x0   96w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/192x0 192w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/240x0 240w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/320x0 320w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/375x0 375w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/425x0 425w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/625x0 625w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/769x0 769w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/825x0 825w,
                    https://a.storyblok.com/f/157376/944x608/3602390d58/group-1005-copie.jpg/m/      944w
                  "
                  alt
                  width="944"
                  height="608"
                  loading="lazy"
                  sizes="(min-width: 769px) 472px, 100vw"
                />
              </div>
              <div class="HWGridService">
                <div class="parentServiceGrid ">
                  <div class="divSG1">
                    <img
                      src="https://a.storyblok.com/f/157376/x/52d1a34770/salesforce_blue.svg"
                      alt
                      loading="lazy"
                    />
                  </div>
                  <div class="divSG2">
                    <img
                      src="https://a.storyblok.com/f/157376/x/be779978ca/hubspot.svg"
                      alt
                      loading="lazy"
                    />
                  </div>
                  <div class="divSG3">
                    <img
                      src="https://a.storyblok.com/f/157376/x/518cc2ec2f/active-campaign.svg"
                      alt
                      loading="lazy"
                    />
                  </div>
                  <div class="divSG4">
                    <img
                      src="https://a.storyblok.com/f/157376/x/a7644c32ef/microsoft-dyn.svg"
                      alt
                      loading="lazy"
                    />
                  </div>
                  <div class="divSG5">
                    <img
                      src="https://a.storyblok.com/f/157376/x/464e185a51/salesloft.svg"
                      alt
                      loading="lazy"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="div32"></div>
        <div class="div33"></div>
        <div class="div34"></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ServiceGrid",
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
.marginLeft {
  margin-left: 20.219em;
}
.marginRight {
  margin-right: 20.219em;
}

.parent3 {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(3, 1fr);
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}

.div31 {
  grid-area: 1 / 1 / 2 / 2;
}
.div32 {
  grid-area: 1 / 2 / 2 / 3;
}
.div33 {
  grid-area: 2 / 1 / 3 / 3;
}
.div34 {
  grid-area: 3 / 1 / 4 / 3;
}

.parentServiceGrid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  grid-template-rows: 1fr;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}

.divSG1 {
  grid-area: 1 / 1 / 2 / 2;
}
.divSG2 {
  grid-area: 1 / 2 / 2 / 3;
}
.divSG3 {
  grid-area: 1 / 3 / 2 / 4;
}
.divSG4 {
  grid-area: 1 / 4 / 2 / 5;
}
.divSG5 {
  grid-area: 1 / 5 / 2 / 6;
}
.HWGridService {
  height: 40px;
  width: 232px;
  padding: 8px;
  position: relative;
}
</style>
