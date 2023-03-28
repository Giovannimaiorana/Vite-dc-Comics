<script>
import ThisFatherMain from './ThisFatherMain.vue';


export default {
    components: {
        ThisFatherMain,

    },

    props: {
        img: String,
        text: String
    }
}
</script>

<template>
    <div class="containermain">
        <div class="jumboTron">

        </div>

        <div class="cardlist">

            <ThisFatherMain />



        </div>
    </div>
</template>

<style scoped>
.jumboTron {
    width: 100%;
    height: 370px;
    background-image: url(../public/jumbotron.jpg);
}

button {
    border: none;
    width: 150px;
    background-color: rgb(5, 130, 249);
    color: white;
    padding: 10px;
    margin-top: 20px;
    margin-bottom: 20px;
}

.cardlist {
    width: 100%;
    background-color: rgb(27, 27, 27);

}
</style>