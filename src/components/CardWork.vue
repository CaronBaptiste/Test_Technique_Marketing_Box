<template>
    <div class="miroir">
      <div class="card">
        <div class="card_flex">
          <div class="card_flex_width">
            <div class="card_flex_align_items">
              <div class="card_img_flex">
                <img class="miroir card_img_flex_width" src="./../assets/CardWork.webp" alt="image">
              </div>
            </div>
          </div>
          <div class="miroir card_flex_txt">
            <div>
              <p class="card_flex_txt_title">Facilitez le télétravail</p>
              <p class="card_flex_txt_subtitle">Gérez efficacement vos équipes en télétravail grâce à la téléphonie 100% cloud et assurez la continuité de votre activité où que vous soyez.</p>
              <button class="card_flex_button">En savoir plus</button>
            </div>
  <div class="card_flex_resume" style="">
              <div class="card_flex_resume_fd">
                <div style="width: 60%;">
                  <div class="card_flex_resume_logo">
                    <img class="card_flex_resume_logo_width" src="./../assets/48x0.webp" alt="">
                  </div>
                </div>
                <div style="padding: 20px;">
                  <p style="font-size: 20px;">Anton Zillberberg</p>
                  <p style="font-size: 15px;">CEO et Fondateur, QuickStay</p>
                  <p style="color: #afbbc0;">"Nous avons évalué plusieurs fournisseurs et Aircall était le seul qui permette une telle flexibilité et un tel niveau de personnalisation pour notre service à la clientèle et nos pratiques commerciales." </p>
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
    name: "CardWork",
  };
  </script>
  
  <style scoped>
  p{
    color: black;
  }
  .miroir{
    display: inline-block;
    transform: scaleX(-1);
  }
  .card{
    background-color: #f7f8fc;
    border-radius: 60px;
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
    background-color: white;
    border-radius: 30px;
    display: flex;
    width: 100%;
  }
  .card_img_flex{
    display: flex;
    
  }
  .card_img_flex_width{
    width: 90%;
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
    font-size: 35px;
    font-weight: bold;
  }
  .card_flex_txt_subtitle{
    color: #afbbc0;
    font-size: 17px;
    padding: 20px 0px 20px 0px;
  }
  .card_flex_button{
    margin-bottom: 40px;
    background-color: #00bd82;
    border-radius: 25px; 
    padding: 13px;
    margin-top: 10px; 
    color: white;
  }
  .card_flex_button:hover{
    background-color: #00724e;
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