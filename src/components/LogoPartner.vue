<template>
  <section style="background-color: #06374b; margin: 60px 0px">
    <div class="parent_logo_partner">
      <div class="div_content">
        <h1>La téléphonie d'entreprise connectée à vos outils</h1>
        <div class="logo_large_parent">
          <div class="logo_large_flex_grid1">
            <img
              src="https://a.storyblok.com/f/157376/x/52d1a34770/salesforce_blue.svg"
              alt=""
            />
            <div>
              <p class="logo_large_title">Selsforce</p>
              <p class="logo_large_subtitle">CRM</p>
            </div>
          </div>
          <div class="logo_large_flex_grid2">
            <img
              src="https://a.storyblok.com/f/157376/x/be779978ca/hubspot.svg"
              alt=""
            />
            <div>
              <p class="logo_large_title">HubSport</p>
              <p class="logo_large_subtitle">CRM</p>
            </div>
          </div>
          <div class="logo_large_flex_grid3">
            <img
              src="https://a.storyblok.com/f/157376/x/5d6c806328/zendesk.svg"
              alt=""
            />
            <div>
              <p style="padding-left: 0" class="logo_large_title">Zendesk</p>
              <p class="logo_large_subtitle">Help Desk</p>
            </div>
          </div>
          <div class="logo_large_flex_grid4">
            <img
              src="https://a.storyblok.com/f/157376/x/2a5d2edee5/intercom.svg"
              alt=""
            />
            <div>
              <p
                style="justify-content: start; display: flex"
                class="logo_large_title"
              >
                Intercom
              </p>
              <p class="logo_large_subtitle">Help Desk - Live Chat</p>
            </div>
          </div>
        </div>
        <div class="logo_large_parent2">
          <div class="logo_large_flex_grid21" style="padding-left: 15px">
            <img
              src="https://a.storyblok.com/f/157376/x/cd126f7120/monday-com.svg"
              alt=""
              class="img_large"
            />
            <div>
              <p class="logo_large_title">monday.com</p>
              <p class="logo_large_subtitle">CRM</p>
            </div>
          </div>
          <div class="logo_large_flex_grid22">
            <img
              src="https://a.storyblok.com/f/157376/x/c0d4bc79bb/shopify.svg"
              alt=""
            />
            <div>
              <p
                class="logo_large_title"
                style="justify-content: start; display: flex"
              >
                Shopify
              </p>
              <p class="logo_large_subtitle">Ecommerce</p>
            </div>
          </div>
          <div class="logo_large_flex_grid23">
            <img
              src="https://a.storyblok.com/f/157376/x/a78656d8c3/gorgias.svg"
              alt=""
            />
            <div>
              <p
                class="logo_large_title"
                style="justify-content: start; display: flex"
              >
                Gorgias
              </p>
              <p class="logo_large_subtitle">Ecommerce</p>
            </div>
          </div>
          <div class="logo_large_flex_grid24">
            <img
              src="https://a.storyblok.com/f/157376/x/4873b05408/microsoft-teams.svg"
              alt=""
            />
            <div>
              <p class="logo_large_title">Microsoft teams</p>
              <p class="logo_large_subtitle">Productivité</p>
            </div>
          </div>
        </div>
        <p class="card_txt_end">
          Découvrez nos plus de 100 autres intégrations
        </p>
        <div class="parent_logo_partner_litle">
          <img
            class="logo_litle1"
            src="https://a.storyblok.com/f/157376/x/d05c386fee/pipedrive.svg"
            alt=""
          />
          <img
            class="logo_litle2"
            src="https://a.storyblok.com/f/157376/x/50b1da2ac8/make.svg"
            alt=""
          />
          <img
            class="logo_litle3"
            src="https://a.storyblok.com/f/157376/x/af400345a4/edesk.svg"
            alt=""
          />
          <img
            class="logo_litle4"
            src="https://a.storyblok.com/f/157376/x/4b6bfb6d51/bulhorn.svg"
            alt=""
          />
          <img
            class="logo_litle5"
            src="https://a.storyblok.com/f/157376/x/53afd2043b/outreach.svg"
            alt=""
          />
          <img
            class="logo_litle6"
            src="https://a.storyblok.com/f/157376/x/b1cee1a533/kustomer.svg"
            alt=""
          />
          <img
            class="logo_litle7"
            src="https://a.storyblok.com/f/157376/x/10fd3c47c9/typeform.svg"
            alt=""
          />
          <img
            class="logo_litle8"
            src="https://a.storyblok.com/f/157376/x/789fa7f522/jiminny.svg"
            alt=""
          />
          <img
            class="logo_litle9"
            src="https://a.storyblok.com/f/157376/x/e28fd99fb3/sakari.svg"
            alt=""
          />
          <img
            class="logo_litle10"
            src="https://a.storyblok.com/f/157376/x/a34648dd31/segment.svg"
            alt=""
          />
          <img
            class="logo_litle11"
            src="https://a.storyblok.com/f/157376/x/f95d1fe065/snapcall.svg"
            alt=""
          />
          <img
            class="logo_litle12"
            src="https://a.storyblok.com/f/157376/x/a1a5273621/crisp.svg"
            alt=""
          />
        </div>
        <button>Voir tous les outils</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "LogoPartner",
};
</script>

<style scoped>
.parent_logo_partner_litle {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  grid-template-rows: 1fr;
  grid-column-gap: 20px;
  grid-row-gap: 0px;
  margin: 20px 0;
}

.img_large {
  height: 48px;
  width: 48px;
}
.logo_large_parent2 {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: 1fr;
  grid-column-gap: 30px;
  grid-row-gap: 0px;
  margin-bottom: 20px;
  width: 100%;
}
.logo_large_flex_grid21 {
  padding: 10px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 1 / 2 / 2;
  display: flex;
  align-items: center;
}
.logo_large_flex_grid22 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 2 / 2 / 3;
  display: flex;
}
.logo_large_flex_grid23 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 3 / 2 / 4;
  display: flex;
}
.logo_large_flex_grid24 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 4 / 2 / 5;
  display: flex;
}
button {
  background-color: #fff;
  padding: 12px;
  border-radius: 50px;
  margin-bottom: 90px;
  margin-top: 40px;
}
.card_txt_end {
  margin-top: 30px;
  color: #90a4ad;
  font-size: 20px;
  font-weight: semi-bold;
}
.logo_large_parent {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: 1fr;
  grid-column-gap: 30px;
  grid-row-gap: 0px;
  margin-bottom: 20px;
  width: 100%;
}
.logo_large_flex_grid1 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 1 / 2 / 2;
  display: flex;
}
.logo_large_flex_grid2 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 2 / 2 / 3;
  display: flex;
}
.logo_large_flex_grid3 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 3 / 2 / 4;
  display: flex;
}
.logo_large_flex_grid4 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 4 / 2 / 5;
  display: flex;
}
.logo_litle1 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 1 / 2 / 2;
}
.logo_litle2 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 2 / 2 / 3;
}
.logo_litle3 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 3 / 2 / 4;
}
.logo_litle4 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 4 / 2 / 5;
}
.logo_litle5 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 5 / 2 / 6;
}
.logo_litle6 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 6 / 2 / 7;
}
.logo_litle7 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 7 / 2 / 8;
}
.logo_litle8 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 8 / 2 / 9;
}
.logo_litle9 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 9 / 2 / 10;
}
.logo_litle10 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 10 / 2 / 11;
}
.logo_litle11 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 11 / 2 / 12;
}
.logo_litle12 {
  padding: 15px;
  background-color: #234d5f;
  border-radius: 20px;
  grid-area: 1 / 12 / 2 / 13;
}
h1 {
  color: white;
  font-weight: bold;
  font-size: 36px;
  display: flex;
  justify-content: center;
  padding: 20px;
  min-width: 104px;
  align-items: center;
}

.logo_large_title {
  width: 100%;
  color: #fff;
  font-weight: bold;
  padding-left: 10px;
}
.logo_large_subtitle {
  color: #a8bdc4;
  opacity: 0.7;
  font-weight: bold;
  display: flex;
  padding-left: 10px;
}
.parent_logo_partner {
  display: grid;
  grid-template-columns: 1fr 3fr 1fr;
  grid-template-rows: 1fr;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  padding-top: 30px;
}
.div_content {
  grid-area: 1 / 2 / 2 / 3;
  text-align: center;
}
</style>
