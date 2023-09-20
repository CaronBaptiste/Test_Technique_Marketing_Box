<template>
    <div class="card_wrapper">
        <div>
            <img src="https://a.storyblok.com/f/157376/112x112/ceb3dd4f1e/aircall.png/m/48x0" alt="">
            <p class="card_title">Prêt à déployer la téléphonie de votre entreprise ?</p>
            <p class="card_subtitle">Découvrez la solution maintenant</p>
            <button class="button">Demander une démo</button>
        </div>
    </div>
</template>

<script>
export default{
    name : 'cardDemoBlue',
}
</script>

<style scoped>
.button{
    color: black;
    padding: 15px;
    background-color: #FFF;
    border-radius: 30px;
}
p{
    color: #FFF;
    padding: 20px;
}
.card_wrapper{
    display: flex;
    align-items: center;
    justify-content: center;
    background-image: url(https://a.storyblok.com/f/157376/x/9e447fc1a6/cta-bg.svg);
    text-align: center;
    height: 350px;
    margin-bottom: 400px;
    border-radius: 30px;
    margin: 40px;
}

.card_title{
    font-weight: bold; 
    font-size: 34px;
}
.card_subtitle{
    opacity: .7;
    font-size: 25px;
}
</style>