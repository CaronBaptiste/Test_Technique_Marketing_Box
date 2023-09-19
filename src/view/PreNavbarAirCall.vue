<template>
  <nav class="navStyle">
    <section class="">
      <div class="parentNavbar">
        <div class="divColorLeft"></div>
        <div class="divLogo"> 
          <div class="divLogoStyle d-row">
            <div class="d-row">
              <img style="max-width: 20px;max-height: 20px;" src="https://a.storyblok.com/f/157376/48x49/1f377a39ad/calendar-emoji.png/m/" alt="logo prenavbar">
              <p class="para">Webinar : Découvrez comment Aircall utilise sa propre solution pour mieux vendre. <span style="text-decoration: underline;">S’inscrire !</span></p>
            </div>
            <div>
            </div>
          </div>
        </div>
        <div class="divLogo2">  
          <div class="divDropdown ">
          <div>
            <button class="paddingButtons">
              Devenir partenaire
          <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M4.90391 3.38684L8.24357 0.0471853L9.19486 0.99848L4.89716 5.28943L0.603516 0.991734L1.55481 0.0336914L4.90391 3.38684Z" fill="#80939A"></path>
          </svg>
            </button>
          </div>
          <div>
            <button class="paddingButtons">
              Entreprise
                <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4.90391 3.38684L8.24357 0.0471853L9.19486 0.99848L4.89716 5.28943L0.603516 0.991734L1.55481 0.0336914L4.90391 3.38684Z" fill="#80939A"></path>
              </svg>
            </button>
          </div>
          <div>
            <button class="paddingButtons">
              Contactez-nous  
            </button>
          </div>
          <div>
            <button class="paddingButtons buttonTel">
              + 33 1 76 36  06 95  
            </button>
          </div>  
          <div>
            <button class="paddingButtons">
              Login
            </button>
          </div>  
          <div>
            <button class="paddingButtons">
              FR
              <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
               <path d="M4.90391 3.38684L8.24357 0.0471853L9.19486 0.99848L4.89716 5.28943L0.603516 0.991734L1.55481 0.0336914L4.90391 3.38684Z" fill="#80939A"></path>
              </svg>
            </button>
          </div>
        </div>
        </div>
      </div>
    </section>
  </nav>
</template>
<script>
export default {
  name: "NavbarAirCall",
};
</script>

<style scoped>
.buttonTel{
  background-color: #38bc93;
  border-radius: 20px;
  padding: 5px !important;
}
button{
  font-size: 13px;
  color: #FFF;
}
.para{
  color: #FFF;
  font-size: 13px;
  line-height: 15px;
  max-width: 85%;
  padding: 5px;
}
.d-row{
  display: flex;
  flex-direction: row;
  align-items: center;
}
.navStyle{
  background-color: #06ab78;
  border-bottom: solid 0.5px #eaebf0;
}
.parentNavbar {
  display: grid;
  grid-template-columns: .5fr repeat(2, 1fr) .5fr;
  grid-template-rows: repeat(1, 1fr);
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}

.divLogo { 
  grid-area: 1 / 2 / 2 / 3; 
  display: flex;
  justify-content: start;
  align-items: center;
  justify-items: start;
  background-color: #20b486;
  border-radius: 0px 20px 20px 0px;
}
.divLogo2 { grid-area: 1 / 3 / 2 / 4; }
.alignNav{
  display: flex;
  flex-direction: row;
}


.divDropdown { grid-area: 1 / 3 / 2 / 4;
  display: flex;
  flex-direction: row;
  align-items: center;
}
.paddingButtons{
  padding: 11px;
}
/* .paddingButtons2{
  padding: 16px;
} */
.divButton { grid-area: 1 / 4 / 2 / 5;
  display: flex;
  flex-direction: row;
  align-items: center;
}
.divColorLeft { 
  grid-area: 1 / 1 / 2 / 2; 
  background-color: #20b486;
}
</style>
