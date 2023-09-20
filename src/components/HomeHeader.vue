<template>
    <div class="padding center parent " >
        <div class="div1 wrapper" > 
            <h1 class="HomeHeaderTitle">La téléphonie d'entreprise connectée à vos outils</h1>
            <p class="pStyle" >Facile à installer. Simple à utiliser. Intégrée à vos outils.</p>
            <div class="boxInput">
                <div style="padding: 10px;">
                    <input type="email" placeholder="Email professionel">
                </div>
                <div>
                    <button class="btnStyle_txt">
                        Essai gratuit
                    </button>
                </div>
            </div>
        </div>
        <div class="div2">
            <img src="https://a.storyblok.com/f/157376/1328x1568/f7dcb5e4a0/hero-fr.jpg/m/" alt="" class="imgStyle">
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeHeader',
}
</script>

<style scoped>
input::placeholder{
    color: #d1d8db;
}
.boxInput{
    padding: 8px;
    height: 60px;
    width: 70%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    border-radius: 30px;
    border: 1px solid rgba(2,40,45,.2);
    box-shadow: 0 24px 48px rgba(2,40,45,.05);
}

.wrapper{
    flex-wrap: wrap;
    font-size: 18px;
    font-weight: 400;
}

.center {
    display: flex;
    justify-content: center;
    align-items: center;
}

.padding {
    padding-top: 2em;
    padding-left: 1em;
    padding-right: 1em;
    padding-bottom: 6em;
}

.imgStyle {
    object-fit: cover;
    height: 500PX;
    min-width: 500px;
    border-radius: 5% 5% 5% 5%;
}

.parent {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr;
    grid-column-gap: 0px;
    grid-row-gap: 0px;
}

.div1 {
    grid-area: 1 / 1 / 2 / 2;
    min-width: 650px;
}

.div2 {
    grid-area: 1 / 2 / 2 / 3;
    display: flex;
    justify-content: flex-end;
}

.HomeHeaderTitle{
    font-size: 54px;
    line-height: 64px;
    color:rgb(1, 38, 53) ;
    width: 100%;
}

.pStyle{
    color: rgb(1, 38, 53);
    font-size: 20px;
    line-height: 32px;
    font-weight: 400;
    margin-bottom: 32px;
    box-sizing: border-box;
}
.btnStyle_txt:hover{
  transition: 0.5s;
  background-color: #00724e;
}
.btnStyle_txt{
  border-radius: 30px;
  padding: 10px 24px;
  color: #FFF;
  background-color: #00bd82;
  font-weight: 500;
}

</style>