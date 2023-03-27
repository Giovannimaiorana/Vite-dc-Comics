<script>
export default {
    data() {
        return {
            footerlink: [
                {
                    name: 'CHARACTERS',
                },
                {
                    name: 'COMICS',
                },
                {
                    name: 'MOVIES',
                },
                {
                    name: 'TV',
                },
                {
                    name: 'GAMES',
                },
                {
                    name: 'VIDEOS',
                },
                {
                    name: 'NEWS',
                },

            ],
            shopfooter: [
                {
                    name: 'Shop Dc',
                },
                {
                    name: 'Shop Dc colle',
                },
            ],
            footerdc: [
                {
                    name: 'Terms Of Use',
                },
                {
                    name: 'Privacy policy (New)',
                },
                {
                    name: 'Ad Choices',
                },
                {
                    name: 'Advertaising',
                },
                {
                    name: 'Jobs',
                },
                {
                    name: 'Subscription',
                },
                {
                    name: 'Talent Workshop',
                },
                {
                    name: 'CPSC Certificates',
                },
                {
                    name: 'Ratings',
                },
                {
                    name: 'Shop Help',
                },
                {
                    name: 'Contact Us',
                },

            ],
            footersites: [
                {
                    name: 'DC',
                },
                {
                    name: 'MAD Magazine',
                },
                {
                    name: 'DC Kids',
                },
                {
                    name: 'DC Universe',
                },
                {
                    name: 'DC Power Visa',
                },


            ],

        }
    }

}
</script>

<template>
    <div class="containerfooterTop">
        <div class="contentfooter">
            <div class="containerContentfooterleft">
                <div>
                    <h3>DC COMICS</h3>
                    <p>
                    <ul>
                        <li v-for="element in footerlink ">{{ element.name }}</li>

                    </ul>
                    </p>

                    <h3>SHOP</h3>
                    <ul>
                        <li v-for="element in shopfooter">{{ element.name }}</li>
                    </ul>
                </div>
                <div>
                    <h3>DC </h3>
                    <p>
                    <ul>
                        <li v-for="element in footerdc">{{ element.name }}</li>

                    </ul>
                    </p>
                </div>
                <div>
                    <h3>SITES </h3>
                    <p>
                    <ul>
                        <li v-for="element in footersites">{{ element.name }}</li>

                    </ul>
                    </p>
                </div>
            </div>
            <div class="containerContentright">
                <div class="logofooter">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>


        </div>


    </div>
</template>

<style scoped>
.logofooter img {
    width: 400px;
    margin-right: 50px;
}

.contentfooter {
    width: 1300px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    flex-direction: row;


}

.containerfooterTop {
    width: 100%;
    max-height: 400px;
    background-image: url(../assets/img/footer-bg.jpg);

}

h3 {
    color: white;
    padding: 15px;
}

ul {
    list-style: none;
    color: lightgray;
}

ul li {
    font-size: 10px;
    margin-top: 10px;
}

li:hover {
    color: blue;
}

.containerContentfooterleft {
    display: flex;
    padding-top: 30px;
    padding-bottom: 30px;

}
</style>