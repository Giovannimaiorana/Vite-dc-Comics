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
            <img :src="img">
            <h2> {{ text }} ciao</h2>
        </div>
    </div>
</template>

<style scoped>
.containermain {}

.jumboTron {
    width: 100%;
    height: 370px;
    background-image: url(../public/jumbotron.jpg);
}

.cardlist {
    width: 100%;
    background-color: rgb(27, 27, 27);
    display: flex;
    flex-wrap: wrap;
}

h2 {
    color: white;
    font-size: 15px;
}

.cardlist img {}
</style>