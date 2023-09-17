<template>
  <section class="marginLeft marginRight center paddingLR" style="padding: 64px;">
    <div class="flex-wrap">
      <div class="center">
        <h2 class="center" style="width: 764px; height: 104px; font-weight: bold;">Une mise en place rapide pour une téléphonie cloud sur mesure</h2>
      </div>
      <div class="center">
        <div class="parent2">
          <!-- Video1 -->
          <div class="div21" style="padding-left: 24px; margin-bottom: 48px;">
            <video
              class="videoStyle"
              muted
              playsinline
              preload="metadata"
              loop
              autoplay
            >
              <source
                src="https://a.storyblok.com/f/157376/x/5b4fac320c/set-up-in-second-fr.mp4"
                type="video/mp4"
              />
            </video>
            <h3 class="center marginB1">Mise en place en 3 min</h3>
            <div class="center marginB1">
              <p style="width: 498px">
                Découvrez notre solution 100% cloud que vous pouvez installer
                rapidement pour appeler partout dans le monde.
              </p>
            </div>
            <span class="center"> toute nos fonction </span>
          </div>
              <!-- Video2 -->
          <div class="div22" style="padding-left: 24px; margin-bottom: 48px">        
              <video
                class="videoStyle"
                muted
                playsinline
                preload="metadata"
                loop
                autoplay
              >
                <source
                  src="https://a.storyblok.com/f/157376/x/9a57bbb17f/connect-to-your-tools-fr.mp4"
                  type="video/mp4"
                />
              </video>
              <h3 class="center marginB1">Connectez vos outils</h3>
            <div class="center marginB1">
              <p style="width: 498px">
             Améliorez vos appels avec la remontée de fiches. Intégrez Aircall à vos outils CRM, Service Client et vos autres applications.
              </p> 
            </div>      
            <span class="center"> voir notre marketplace </span>
          </div>

            <!-- Video3 -->
          <div class="div23">
            <video
              class="videoStyle"
              muted
              playsinline
              preload="metadata"
              loop
              autoplay
            >
              <source
                src="https://a.storyblok.com/f/157376/x/1c2b1f084d/gain-visibility-fr.mp4"
                type="video/mp4"
              />
            </video>
            <h3 class="center marginB1">Mesurer vos KPI</h3>
            <div class="center marginB1">
              <p style="width: 498px">
             Analysez les bons indicateurs en temps réel pour prendre les bonnes décisions au bon moment.
              </p>
            </div>
            <span class="center"> Gardez un oeil sur vos KPI  </span>
          </div>
              <!-- Video4 -->
          <div class="div24" style="padding-left: 24px; margin-bottom: 48px">
            <video
              class="videoStyle"
              muted
              playsinline
              preload="metadata"
              loop
              autoplay
            >
              <source
                src="https://a.storyblok.com/f/157376/x/3e1d3554f7/enable-productivity-fr.mp4"
                type="video/mp4"
              />
            </video>
            <h3 class="center marginB1">Améliorer votre productivité</h3>
            <div class="center marginB1">
              <p style="width: 498px">
               Créez rapidement de nouveaux process, numéros et groupes de compétences quand vous en avez besoin.
              </p>
            </div>
            <span class="center"> Découvrez nos cas clients</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ProductGrid",
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
.videoStyle {
  width: 31.125em;
  height: 13.188em;
  margin-bottom: 1em;
}
.marginB1 {
  margin-bottom: 1em;
}
.videoRadius {
  margin-bottom: 1em;
  border-top-right-radius: 5%;
  border-top-left-radius: 5%;
  border-bottom-right-radius: 5%;
  border-bottom-left-radius: 5%;
}
.parent2 {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, 1fr);
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}

.div21 {
  grid-area: 1 / 1 / 2 / 2;
}
.div22 {
  grid-area: 1 / 2 / 2 / 3;
}
.div23 {
  grid-area: 2 / 1 / 3 / 2;
}
.div24 {
  grid-area: 2 / 2 / 3 / 3;
}
</style>
