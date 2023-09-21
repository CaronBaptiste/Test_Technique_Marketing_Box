<template>
    <div class="parent_card_blue">
        <div class="card_wrapper card_blue_grid">
            <div class="">
                <img src="https://a.storyblok.com/f/157376/112x112/ceb3dd4f1e/aircall.png/m/48x0" alt="">
                <p class="card_title">Prêt à déployer la téléphonie de votre entreprise ?</p>
                <p class="card_subtitle">Découvrez la solution maintenant</p>
                <button class="button">Demander une démo</button>
            </div>
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

.parent_card_blue{
    display: grid;
    grid-template-columns: 1fr 3fr 1fr;
    grid-template-rows: 1fr;
    grid-column-gap: 0px;
    grid-row-gap: 0px;
}
.card_blue_grid{
    grid-area: 1 / 2 / 2 / 3;
}
.card_wrapper{
    display: flex;
    align-items: center;
    justify-content: center;
    background-size: cover;
    background-image: url(https://a.storyblok.com/f/157376/x/9e447fc1a6/cta-bg.svg);
    text-align: center;
    height: 350px;
    margin-bottom: 400px;
    border-radius: 30px;
    margin: 40px 0px;
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