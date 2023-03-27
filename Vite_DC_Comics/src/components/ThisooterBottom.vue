<script>
export default {
    data() {
        return {
            loghi: [
                {
                    immagine: "/footer/facebook.png"
                }
            ]
        }
    }
}
</script>

<template>
    <div class="containerfooterbottom">
        <div class="contentfooterbottom">
            <div>
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="sociallogo">
                <h3>FOLLOW US</h3>
                <ul>
                    <li v-for="element in loghi"> <img :src="element.immagine" alt=""></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
.containerfooterbottom {
    width: 100%;
    background-color: rgb(48, 48, 48);

}

.contentfooterbottom {
    width: 1300px;
    height: 100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

button {
    background-color: rgb(48, 48, 48);
    color: white;
    padding: 15px;
    border: none;
    border: 1px solid rgb(46, 130, 249);
}

h3 {
    color: rgb(46, 130, 249);
}

ul {
    list-style: none;
    color: white;
}

.sociallogo {
    display: flex;
    align-items: center;
}
</style>