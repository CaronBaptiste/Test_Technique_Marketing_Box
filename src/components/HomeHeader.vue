<template>
    <div class="padding center parent marginLeft marginRight" style="width: 76.5em;">
        <div class="div1 center " style="background-color: aqua;"> tél</div>
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
.center {
    display: flex;
    justify-content: center;
}

.padding {
    padding-top: 2em;
    padding-left: 1em;
    padding-right: 1em;
    padding-bottom: 6em;
}

.imgStyle {
    height: 31.25em;
    width: 31.25em;
    border-top-right-radius: 5%;
    border-top-left-radius: 5%;
    border-bottom-right-radius: 5%;
    border-bottom-left-radius: 5%;
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
}

.div2 {
    grid-area: 1 / 2 / 2 / 3;
}</style>