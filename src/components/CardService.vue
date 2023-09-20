<template>
    <div class="d-col card">
        <div>
            <div>
                <img class="card_img_width" :src="image" alt="image" >
            </div>
            <div>
                <p class="card_title">
                    {{ cardTitle }}
                </p>
                <p class="card_subtitle">
                    {{  cardSubtitle }}
                </p>
                <button class="card_button">
                    {{ cardButton }}
                </button>
            </div>
        </div>
        <div class="card_resume">
            <div class="card_resume_logo_row">
                <div style="width: 20%;">
                    <img style="width: 70%;border-radius: 30px;" :src="logo" alt="logo" >
                </div>
                <div style="width: 80%;">
                    <p>{{ name }}</p>
                    <p>{{ title }}</p>
                    <p style="padding-top: 10px; color: #4d6771;">"{{ subtitle }}"</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default{
        name:'CardService',
        props:{
            image:{
                type: String,
                required: true
            },
            cardTitle:{
                type: String,
                required: true 
            },
            cardSubtitle:{
                type: String,
                required: true 
            }, 
            cardButton:{
                type: String,
                required: true 
            },
            name:{
                type: String,
                required: true 
            },
            logo:{
                type: String,
                required: true
            },
            title:{
                type: String,
                required: true 
            },
            subtitle:{
                type: String,
                required: true 
            },
        }
    }
</script>

<style scoped>
.d-col{
    display: flex;
    flex-direction: column;
}
.card{
    background-color: #f7f8fc;
    border-radius: 30px;
    margin: 50px;
    border-radius: 60px;
    min-width: 100%;
    padding: 60px;
}
.card_img_width{
    width: 100%; 
    border-radius: 30px;
    padding: 20px;
}
.card_title{
    font-size: 30px;
    font-weight: bold;
    padding: 10px 0px;
}
.card_subtitle{
    color: #4a6570;
    padding-bottom: 10px;
}
.card_button{
    border-radius: 20px;
    padding: 10px;
    background-color: #00bd82;
    color: #FFF;
}

.card_resume{
    margin: 16px;
    padding: 16px;
    background-color: #ffffff;
    border-radius: 20px;
    display: flex;
}

.card_resume_logo_row{
    display: flex;
    flex-direction: row;
}
</style> 