<template>
    <div>
      <div class="card">
        <div class="card_flex">
          <div class="card_flex_width">
            <div class="card_flex_align_items">
              <div class="card_img_flex">
                <img class="card_img_flex_width" src="./../assets/CardConnect.webp" alt="image">
              </div>
            </div>
          </div>
          <div class="miroir card_flex_txt">
            <div>
              <p class="card_flex_txt_title">Connectez vos outils</p>
              <p class="card_flex_txt_subtitle">Connectez facilement Aircall à vos différents outils CRM et Service Client. Consignez vos appels automatiquement dans les bonnes fiches clients avec toutes les données disponibles (durée d'appels, temps d'attente, enregistrement des conversations...)</p>
              <button class="card_flex_button">Renforcez le travail d'équipe</button>
            </div>
  <div class="card_flex_resume">
              <div class="card_flex_resume_fd">
                <div style="width: 60%;">
                  <div class="card_flex_resume_logo">
                    <img class="card_flex_resume_logo_width" src="./../assets/freenow.svg" alt="">
                  </div>
                </div>
                <div style="padding: 20px;">
                  <p style="font-size: 20px;">Julien Poyet</p>
                  <p style="font-size: 15px;">Customer Service Manager, Kapten</p>
                  <p style="color: #afbbc0;">"Aircall peut nous aider à accompagner notre croissance et notre développement international, grâce à sa simplicité de déploiement et d'utilisation, ainsi que son fonctionnement dans tous les pays." </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "CardConnect",
  };
  </script>
  
  <style scoped>
  p{
    color: #FFF;
  }
  .card{
    background-color: #012635;
    border-radius: 60px;
    margin-bottom: 20px;
  }
  .card_flex{
    display: flex;
    flex-direction: row;
    padding: 70px;
  }
  .card_flex_width{
    border-radius: 20px;
    max-width: 50%;
  }
  .card_flex_align_items{
    display: flex;
    align-items: center;
  }
  .card_flex_resume{
    background-color: #1b3c4a;
    border-radius: 30px;
    display: flex;
    width: 100%;
  }
  .card_img_flex{
    display: flex;
    padding-right: 30px;
  }
  .card_img_flex_width{
    width: 100%;
    height: 100%;
    border-radius: 20px;
  }
  .card_flex_txt{
    max-width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .card_flex_txt_title{
    font-size: 30px;
    font-weight: bold;
  }
  .card_flex_txt_subtitle{
    color: #afbbc0;
    font-size: 17px;
    padding: 0px 0px 20px 0px;
  }
  .card_flex_button{
    margin-bottom: 40px;
    background-color: #FFF;
    border-radius: 25px; 
    padding: 13px;
    margin-top: 10px; 
    color: black;
    transition: color 0.3s;
  }
  .card_flex_button:hover{
    background-color: #34515d;
  }
  .card_flex_resume_fd{
    display: flex;
    flex-direction: row;
  }
  .card_flex_resume_logo{
    width: 100%;
    height: 100%;
    display: flex;
    place-content: flex-start flex-end;
    border-radius: 50px;
    align-items: flex-start;
    padding-top: 20px;
  }
  .card_flex_resume_logo_width{
    max-width: 50%;
    border-radius: 50px;
  }
  </style>