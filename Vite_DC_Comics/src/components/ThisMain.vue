<script>
export default {
    data() {
        return {
            shop: [
                {

                    name: 'DIGITAL COMICS',
                    img: "../assets/img/buy-comics-digital-comics.png"
                },
                {
                    name: 'DC MERCHANDISE',
                    img: "/buy-comics-merchandise.png",
                },
                {
                    name: 'SUBSCRIPTION',
                    img: "/buy-comics-subscriptions.png",

                },
                {
                    name: 'COMIC SHOP LOCATOR',
                    img: "/buy-comics-shop-locator.png",
                },
                {
                    name: 'DC POWER VISA',
                    img: "/buy-dc-power-visa.svg",
                },

            ]

        }
    }

}
</script>

<template>
    <div class="container_main">
        <div class="contentmain">
            <p> -->Content goes here </p>
        </div>
        <div class="contentloghi">

            <ul>

                <li v-for="element in shop">
                    <img :src="element.img" :alt="element.name">
                    <span>{{ element.name }}</span>
                </li>
            </ul>
        </div>

    </div>
</template>

<style>
.container_main {

    width: 100%;
}

.contentmain {
    height: 100px;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgb(28, 28, 28);
}

.contentloghi {
    height: 100px;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgb(5, 130, 249);
}

.contentloghi ul {
    list-style: none;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
}

ul li {
    margin-left: 10px;
    font-size: 13px;
}

ul img {
    width: 40px;

}

.contentmain p {
    color: white;
    font-size: 30px;

}
</style>