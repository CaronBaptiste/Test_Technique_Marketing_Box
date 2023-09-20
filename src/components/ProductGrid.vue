<template>
  <section
    class="center"
    style="padding: 64px; padding-top: 0;"
  >
    <div class="flex-wrap">
      <div class="center">
        <h2
          class="center h2Style"
          style="width: 764px; height: 104px; font-weight: bold"
        >
          Une mise en place rapide pour une téléphonie cloud sur mesure
        </h2>
      </div>  
      <div class="center">
        <div class="parent2">
          <!-- Video1 -->
          <div
            class="div21 slide-up"
            style="padding-left: 24px; margin-bottom: 48px"
          >
            <video
              class="videoRadius"
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
            <h3 class="center h3Style">Mise en place en 3 min</h3>
            <div class="center">
              <p class="txtColor" style="width: 498px">
                Découvrez notre solution 100% cloud que vous pouvez installer
                rapidement pour appeler partout dans le monde.
              </p>
            </div>
            <a href="" style="text-decoration-line:none ;">
            <span class="center spanStyle"> Toute nos fonctionnalités </span></a>
          </div>
          <!-- Video2 -->
          <div
            class="div22 slide-up"
            style="padding-left: 24px; margin-bottom: 48px"
          >
            <video
              class="videoRadius"
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
            <h3 class="center h3Style">Connectez vos outils</h3>
            <div class="center">
              <p class="txtColor" style="width: 498px">
                Améliorez vos appels avec la remontée de fiches. Intégrez
                Aircall à vos outils CRM, Service Client et vos autres
                applications.
              </p>
            </div>
            <span class="center spanStyle"> Voir notre marketplace </span>
          </div>

          <!-- Video3 -->
          <div class="div23 slide-up">
            <video
              class="videoRadius"
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
            <h3 class="center h3Style">Mesurer vos KPI</h3>
            <div class="center">
              <p class="txtColor" style="width: 498px">
                Analysez les bons indicateurs en temps réel pour prendre les
                bonnes décisions au bon moment.
              </p>
            </div>
            <span class="center spanStyle"> Gardez un oeil sur vos KPI </span>
          </div>
          <!-- Video4 -->
          <div
            class="div24 slide-up"
            style="padding-left: 24px; margin-bottom: 48px"
          >
            <div>
              <video
                class="videoRadius"
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
            </div>
            <h3 class="center h3Style">Améliorer votre productivité</h3>
            <div class="center marginB1">
              <p class="txtColor" style="width: 498px">
                Créez rapidement de nouveaux process, numéros et groupes de
                compétences quand vous en avez besoin.
              </p>
            </div>
            <span class="center spanStyle"> Découvrez nos cas clients</span>
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

.videoRadius {
  height: 211px;
  width: 497.984px;
  display: block;
  box-sizing: border-box;
  margin-bottom: 1em;
  border-top-right-radius: 24px;
  border-top-left-radius: 24px;
  border-bottom-right-radius: 24px;
  border-bottom-left-radius: 24px;
  object-fit: cover;
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
.txtColor {
  display: block;
  color: rgba(1, 38, 53, 0.5);
  font-size: 18px;
  font-weight: 400;
  line-height: 26px;
  margin-bottom: 16px;
  text-align: center;
}
.spanStyle {
  color: rgba(1, 38, 53);
  font-size: 18px;
  font-weight: 600;
  line-height: 26px;
  height: auto;
  text-align: center;
  background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTEyLjgzIDEyLjAwNmwtMy44MTUtMy44OUwxMC4xMDEgNyAxNSAxMi4wMDIgMTAuMDk0IDE3IDkgMTUuODg0bDMuODMtMy44Nzh6IiBmaWxsPSIjMDBCRDgyIi8+PC9zdmc+Cg==);
  background-position: right center;
  background-repeat: no-repeat;
  background-size: var(--icon-width);
  transition: color 0.3s;
}

/* .spanStyle::after {
  margin-right: 0;
  margin-left: 5px;
  margin-right: -10px;
  transition: margin-right 0.3s;
} */

/* .spanStyle:hover::after{
  margin-right: 0 ;
} */

.spanStyle:hover{
  color: #00a859;
  padding-right: 10px;
}

.h2Style {
  color:rgb(1, 38, 53) ;
  display: block;
  font-size: 38px;
  font-weight: 900;
  line-height: 52px;
  margin-block-end: 24px;
  margin-bottom: 64px;
  margin-inline-end: 239px;
  margin-inline-start: 239px;
  margin-left: 239px;
  margin-right: 239px;
  max-width: 746px;
  text-align: center;
}

.h3Style {
  display: block;
  margin-bottom: 16px;
  font-size: 32px;
  text-align: center;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  white-space: pre-wrap;
  font-weight: bold;
}

.slide-up {
  position: relative;
  animation: slideUp 1s ease forwards;
}

@keyframes slideUp {
  from {
    transform: translateY(100%);
  }
  to {
    transform: translateY(0);
  }
}
</style>
